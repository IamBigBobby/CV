# Denis Svetleishii
## Junior Frontend Developer
_____
## Contact informaition:

Phone: +7 953 866 06 32  
E-mail: denissvetleishii@outlook.com  
Telegram: @Denis_Svetleishii
## About Myself:
I used to work as an engineer in a construction laboratory. The work consisted in laboratory control of building materials. I have technical experience that always helps me.
And now for 9 years I'm working as a swimming coach for preschoolers and children with special needs. This job gave me great inspiration (thanks to the children) to learn new things.
I think that the combination of my past experience helps me to make a good products and be a good employee.
___
## Skills and Proficiency:
* HTML5, CSS3
* JavaScript Basics
* Git, GitHub
* VS Code
## Code example 
```
const MORSE_TABLE = {
                        '.-':     'a',
                        '-...':   'b',
                        '-.-.':   'c',
                        '-..':    'd',
                        '.':      'e',
                        '..-.':   'f',
                        '--.':    'g',
                        '....':   'h',
                        '..':     'i',
                        '.---':   'j',
                        '-.-':    'k',
                        '.-..':   'l',
                        '--':     'm',
                        '-.':     'n',
                        '---':    'o',
                        '.--.':   'p',
                        '--.-':   'q',
                        '.-.':    'r',
                        '...':    's',
                        '-':      't',
                        '..-':    'u',
                        '...-':   'v',
                        '.--':    'w',
                        '-..-':   'x',
                        '-.--':   'y',
                        '--..':   'z',
                        '.----':  '1',
                        '..---':  '2',
                        '...--':  '3',
                        '....-':  '4',
                        '.....':  '5',
                        '-....':  '6',
                        '--...':  '7',
                        '---..':  '8',
                        '----.':  '9',
                        '-----':  '0',
                    };
                    
                    function decode(expr) {
                        let result = '';
                        
                        const arrExpr = [];
                        for (let i = 0; i < expr.length; i+=10){
                            arrExpr.push(expr.slice(i, i + 10));
                        }
                        
                        const arrEachElement = [];
                        for (let element of arrExpr){
                            if (element == '**********'){
                                arrEachElement.push(' ');
                            }
                            else{
                                arrEachElement.push(element);
                            }
                        }
                    
                        const arrEachElementMorse = [];
                        for (let element of arrEachElement){
                            if (element == ' '){
                                arrEachElementMorse.push(' ');
                            }
                            else{
                                element = element.replace(/10/gi, '.');
                                element = element.replace(/11/gi, '-');
                                element = element.replace(/00/gi, '')
                                arrEachElementMorse.push(element);
                            }
                        }
                    
                        const finalStringResult = [];
                        for(let element of arrEachElementMorse){
                            for (key in MORSE_TABLE){
                                if (element == key){
                                    finalStringResult.push(MORSE_TABLE[key]);
                                }
                                else if (element == ' '){
                                    finalStringResult.push(' ');
                                    break;
                                }
                            }
                        }
                        result = finalStringResult.join('');
                        return result;
                    }
```
___
## Courses:
* JavaScript Manual on learnjavascript.ru (in progress)
* RS Schools Course «JavaScript/Front-end. Stage 0» (in progress)
## Languages
* English - B1
* Russian - Native