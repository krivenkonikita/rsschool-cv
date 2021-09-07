# Resume

## 1. Name

Nikita krivenko

## 5. Code examples

## Absent vowel

    function absentVowel(x){
    let result;
    
    let lettersArray = ['a', 'e', 'i', 'o', 'u'];
    
    lettersArray.map((el, index) => {
        if(!x.includes(el)) {
        result = index;
        }
    })
    
    return result
    }