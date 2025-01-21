# matriz_challenge
matriz challenge


font code: 

let matriz1 = [[1,2], [3,4]]
let matriz2 = [[5,6], [7,8,9]]

let valor1 = []
let valor2 = []

matriz1.forEach(n1 => { 
    n1.forEach(test1=> { 
        valor1.push(test1)
    })
})

matriz2.forEach(n2=> { 
    n2.forEach(test2=> { 
        valor2.push(test2)
    })
})

function teste2(){
    console.log(Number(valor1), Number(valor2))
}


console.log(valor1.length)
console.log(valor2.length)

function teste(){   

    let calcValor1 = valor1.length
    let calcValor2 = valor2.length

   if (calcValor1 == calcValor2) { 
        console.log("As matrizes POSSUEM as mesmas quantidades de colunas e linha")
    } else { 
        console.log("As matrizes NÃO possuem as mesmas quantidades de colunas e linhas")
    }
}
