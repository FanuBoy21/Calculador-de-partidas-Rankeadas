//Rankeador
r(16,5)
// Função parâmetro e Quant. de vitórias(vt) e Quant. de derrota(dt)
function r(vt,dr){
//Saldo de vitórias(vd)
    vd=vt-dr
//Se vitórias for menor 10= Ferro.    
if(vd<=10){console.log('O Héroi tem de saldo '+vd+' está no nível Ferro.')}
//Se vitórias for entre 11 e 20= Bronze.
else if(vd<=11 || vd===20){console.log('O Herói tem de saldo '+vd+' está no nível Bronze.')}
//Se vitórias for entre 21 e 50= Prata.
else if(vd<=21 || vd===50){console.log('O Herói tem de saldo '+vd+' está no nível Prata.')}
//Se vitórias for entre 51 e 80= Ouro.
else if(vd<=51 || vd===80){console.log('O Herói tem de saldo '+vd+' está no nível Ouro.')}
//Se vitórias for entre 81 e 90= Diamante.
else if(vd<=81 || vd===90){console.log('O Herói tem de saldo '+vd+' está no nível Diamante.')}
//Se vitórias for entre 91 e 100= Lendário
else if(vd<=91 || vd===100){console.log('O Herói tem de saldo '+vd+' está no nível Lendário.')}
//Se vitórias for igual ou maior de 101= Irmortal.
else if(vd<=101){console.log('O Herói tem de saldo '+vd+' está no nível Imortal.')}
}