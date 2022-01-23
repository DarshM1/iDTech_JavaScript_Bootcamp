# Creating Sentences Activity
let words = ["This", "is", "JavaScript", "Bootcamp!"];

let sentence = ""

function createSentence (words) {
    for (let i = 0; i < words.length; i++) {
        sentence += words[i] + " ";
    }
    return sentence
}

console.log(createSentence(words));

