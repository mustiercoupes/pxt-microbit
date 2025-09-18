basic.showString("ASK A QUESTION")
basic.showNumber(8)
input.onGesture(Gesture.Shake, () => {
    basic.clearScreen()
    let randomNumber = randint(0, 4)
    if (randomNumber == 4) {
        basic.showString("ASK AGAIN")
    } else if (randomNumber == 3) {
        basic.showString("PROBABLY")
    } else if (randomNumber == 2) {
        basic.showString("YES!)
    } else if (randomNumber == 1) {
        basic.showString("NO!")
    }
    else {
        basic.showString("I DON'T KNOW")
    }
    basic.showNumber(8)
})

