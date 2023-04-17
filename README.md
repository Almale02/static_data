stamps
4 vaci.uw.hu getAns()

function getAns(){
    let gapNum = FindCurrent()

    let ansList = I[gapNum][1]
    for (let i = 0; i < ansList.length; i++){
        console.log(ansList[i][0])
    }
}
