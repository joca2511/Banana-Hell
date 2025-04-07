### Mecânica

- Jogo Singleplayer
    
- Loop principal/Objetivos
    
    - Derrotar inimigos
    - Coletar powerups
    - Derrotar chefes
    - Terminar níveis
    - Acumular o máximo de pontos
    
    

- Regras: 
    
        
    - Jogador tem quantidade limitada de bombas e vidas por nível
    - Jogador perde uma vida e parte de sua barra de powerup se entrar em contato com projétil inimigo
    - Jogador tem uma quantidade limitada (mas regenerável ao tempo) de slow motion
    - Jogador pode "desafiar" chefes, deixando a luta mais difícil ao perder acesso a bombas e vidas.
    
    
- Resultados:
    
    - Incrementais:
        
        - Aumento de velocidade ao adquirir powerups
        - Aumento de poder ao encher a barra de powerup
        - Encher o arsenal de armas
            
        
    - Finais:
        
      - Pontuação final ao terminar o jogo
        
        
    
    
- Atores e seus componentes
    
  - Powerup - Aumenta a velocidade do jogador. Quando chega a certa quantidade, melhora a arma equipada.
  - Projétil - Causa dano contra entidades de grupos opostos (Jogador vs. IA), são codificados por cor (Azul = Jogador, Vermelho = Inimigo).
  - Inimigos - Aparecem em intervalos ao redor do jogador, entrar em contato com eles deve causar dano. Quando morrem, tem chance de aparecer um powerup em seu lugar.
  - Banana - Personagem que o jogador controla, possui armas diferentes, bombas e a habilidade de colocar o jogo em slow-motion.
  - Armas - O jogador consegue desbloquear armas ao longo dos níveis, e as trocar quando voltar ao menu principal.
        
    - Pistola - Arma inicial, atira exatamente na frente do jogador. Em sua forma empoderada, são usadas duas pistolas atirando na mesma direção, mas dos lados do jogador
    - Escopeta - Arma desbloqueada após derrotar o primeiro chefe. Atira vários projéteis em um arco, mas os projéteis desaparecem depois de um tempo. Em sua forma empoderada, ela se tranforma em uma escopeta de cano duplo, atirando o dobro de projéteis.
    - Metralhadora - Arma desbloqueada após derrotar o segundo chefe. Atira projéteis em alta cadência, mas de forma aleatória na frente do jogador. Em sua forma empoderada, ela se transforma em uma minigun, aumentando ao máximo sua cadência
        
  - Bombas - Consumível que o jogador pode utilizar para limpar todos os projéteis inimigos da tela. O jogador ganha as bombas remanescentes no final do nível como pontos.
  - Vidas - O jogador possui vidas por nível, toda vez que o jogador levar dano, ele perde uma vida e solta parte dos powerups adquiridos. O jogador ganha as vidas remanescentes no final do nível como pontos.
    
