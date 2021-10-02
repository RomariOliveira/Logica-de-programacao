# Logica-de-programacao

Algorithm "Eventos Savinis"

var n_evento, idade, d_atual, d_evento, n_part;

write ("Eacolha número do evento")
read n_evento

write ("Palestrante e participante do evento 'n_evento'")
write ("Digite ano, mês e dia do evento de forma numérica")
read d_evento
read d_atual

if  d_evento > d_atual then 
    write ("Insira sua idade")
    read idade
    if  idade >= 18 then

        if  n_part < 100 then
            n_part = n_part + 1
            write ("Cadastro efetuado")        
        else 
            write ("Limite de cadastro excedido")
        endif 
    else
        write ("Não permitido menor de idade")
    endif

else
    write ("Evento já realizado, data inválida")
endif

end


