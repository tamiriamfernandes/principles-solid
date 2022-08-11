# Projeto para o curso de SOLID com CSharp

Projeto em MVC que não estava seguindo padrão SOLID. Cada commit feito foi implementando cada principio.

1 - Responsabilidade Unica: Foi criado uma class LeilaoDao concentrando chamadas para o DB.

2 - Inversão de dependencias: Criado abstração do acesso a dados e implemntado a injeção de dependencia. Diminuindo o acoplamento da aplicação.

3 - Aberto/Fechado - Criado novas classes onde a aplicação fica fechada para alterações e aberta para extensões.

4 - Segragação das interfaces - Segregando as interfaces da Dao (usado CQRS).

5 - Liskov - Criando classes base.
