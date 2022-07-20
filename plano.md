-Usuario ou ADM (S/N)
    -Pede Senha
        ADM
        -Consultar item 
            Printa lista filmes:
            -Filme -Genero
            2D LEG: horarios e sala
            2D DUB: horarios e sala 
            3D LEG: horarios e sala
            3D DUB: horarios e sala

        -Alterar item
            -Filme
                1 -2D LEG: horarios e sala
                2 -2D DUB: horarios e sala
                3 -3D LEG: horarios e sala
                4 -3D DUB: horarios e sala
                    -filme
                    -dimensão
                    -legenda
                    -horarios -> sala
                    -sala -> horario (verificar se já existe o mesmo horario na sala mudada)

        -Adicionar item
            -nome filme:
                -generos
                    - qual dimensão e legenda?
                        -quais os horarios e em quais salas?
                            -deseja criar mais itens para esse filme?  (D/L)
                            -deseja criar outro filme?
                            -voltar ao menu ADM

        -Excluir item
            "o que deseja apagar?"
            -Filme
                -Lista de filmes
            -Dimensão e Legenda
                -Lista de filmes
                    -escolher dimensão e legenda (apaga tudo dentro)
                    -cancelar a operação (volta para Excluir item)
            -Horario e sala
                -Lista de filmes
                    -escolher dimensão e legenda
                        -escolher um horario (apaga horario e sala)
                        -cancelar a operação (volta para Excluir item)
            -Voltar ao menu ADM
            
        USUARIO
        <LISTA DE FILMES>
        -Filmes - Generos
            1 -2D LEG: horarios
            2 -2D DUB: horarios    
            3 -3D LEG: horarios
            4 -3D DUB: horarios
                -horarios
                    <QUATIDADE E LUGAR>
                    -quantos ingressos
                        -quantas meias
                            -poltronas (n° ingressos)
                                <PAGAMENTO>
                                -valor total (conta da quantidade de ingressos e meia)
                                -débito, crédito ou dinheiro
                                -cancelar compra