var cpf_busca = 12345678921; //Troque pelo cpf desejado


console.log(cpf_busca.toString().length, "Digitos");


if (cpf_busca.toString().length == 11) {



    var soma = 0;
    for (var i = 0; i < 9; i++)
        soma += parseInt(cpf_busca.toString().charAt(i)) * (10 - i);
    resto = 11 - (soma % 11);
    if (resto == 10 || resto == 11)
        resto = 0;
    if (resto != parseInt(cpf_busca.toString().charAt(9))) {
        console.log("Invalido");
        return false;
    }
    soma = 0;
    for (i = 0; i < 10; i++)
        soma += parseInt(cpf_busca.toString().charAt(i)) * (11 - i);
    resto = 11 - (soma % 11);
    if (resto == 10 || resto == 11)
        resto = 0;
    if (resto != parseInt(cpf_busca.toString().charAt(10))) {
        console.log("Invalido");
        return false;
    }
    console.log("Valido");
    console.log(cpf_busca);


} else {
    console.log("Invalido");
}


