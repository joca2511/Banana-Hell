### Mecânica

- Jogo Singleplayer
    
- Loop principal/Objetivos
    
    - Derrotar inimigos
    - Coletar xp e powerups
    - Derrotar chefes
    - Terminar níveis
    - Acumular o máximo de pontos
    
    

- Regras: 
    
        
    - Jogador tem quantidade limitada de bombas por nível
    - Jogador perde parte de sua vida se entrar em contato com projétil inimigo
    - Jogador tem uma quantidade limitada (mas regenerável ao tempo) de slow motion
    - Jogador pode "desafiar" chefes, deixando a luta mais difícil ao perder acesso a bombas e vidas.
    
    
- Resultados:
    
    - Incrementais:
        
        - Aumento de stats ao selecionar powerups correspondentes
        - Melhoria de armas ao selecionar powerups correspondentes
            
        
    - Finais:
        
      - Pontuação final ao terminar o jogo
        
        
    
    
- Atores e seus componentes
    
  - Powerups - Uma escolha entre melhorias que o personagem/arma pode adquirir. Aparece quando o jogador aumenta de nível 
  - Projétil - Causa dano contra entidades de grupos opostos (Jogador vs. IA), são codificados por cor (Azul = Jogador, Vermelho = Inimigo).
  - Inimigos - Aparecem em intervalos ao redor do jogador, entrar em contato com eles deve causar dano. Quando morrem, tem chance de aparecer um powerup em seu lugar.
  - Banana - Personagem que o jogador controla, possui armas diferentes, bombas e a habilidade de colocar o jogo em slow-motion.
  - Armas - O jogador consegue desbloquear armas ao aumentar de nível, e selecionar uma delas como principal quando voltar ao menu principal.
        
    - Pistola - Arma inicial, atira exatamente na frente do jogador. Em sua forma empoderada, são usadas duas pistolas atirando na mesma direção, mas dos lados do jogador
    - Escopeta - Atira vários projéteis em um arco, mas os projéteis desaparecem depois de um tempo. Em sua forma empoderada, ela se tranforma em uma escopeta de cano duplo, atirando o dobro de projéteis.
    - Metralhadora - Atira projéteis em alta cadência, mas de forma aleatória na frente do jogador. Em sua forma empoderada, ela se transforma em uma minigun, aumentando ao máximo sua cadência
        
  - Bombas - Consumível que o jogador pode utilizar para limpar todos os projéteis inimigos da tela. O jogador ganha as bombas remanescentes no final do nível como pontos.
  - Vidas - O jogador uma quantidade de vida máxima por nível, toda vez que o jogador levar dano, ele perde uma parte da sua vida. O jogador ganha a vida remanescentes no final do nível como pontos.
    
