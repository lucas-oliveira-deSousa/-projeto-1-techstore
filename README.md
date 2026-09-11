# -projeto-1-techstore
const nome="Lucas Almeida"
const produto="Notebook Gamer"
const preço=4500
const quantidade=2
const subtotal=9000
const estoque=10
const valorPago=9000
console.log(nome)
console.log(produto)
console.log(preço)
console.log(quantidade)
console.log(subtotal)
if(preço>=1000){
        console.log("10%")
}else{
        console.log("0%")
}
console.log(900)

if(quantidade>=2){      
        console.log( "Estoque disponível")
} else{ 
        console.log("estoque indisponivel")
}
console.log(quantidade*preço-900)
let situaçãodopagamento="aguardando pagamento do usuario"
let statusdoestoque="estoque disponivel "
let statusdopedido="aguardando..."
console.log(situaçãodopagamento)
console.log(statusdoestoque)
console.log(statusdopedido)

module.exports = {
    cliente,
    produto,
    preco,
    quantidade,
    estoque,
    valorPago,
    subtotal,
    estoqueDisponivel,
    descontoPercentual,
    valorDesconto,
    valorFinal,
    pagamentoStatus,
    troco,
    statusPedido,
    resumo
}

























