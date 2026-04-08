# Projeto Porta e Senha - Godot

Este é um projeto de revisão para a disciplina de programação em Godot.

## Arquivos

- **porta_senha.txt**: script de uma porta com senha. 
  - Verifica se a senha digitada pelo jogador está correta.
  - Informa se a senha é muito curta ou incorreta.
  - Bloqueia o acesso após 3 tentativas erradas.

- **porta_interativa.txt**: script de porta interativa.
  - A porta só abre quando o jogador está próximo e pressiona a tecla de interação.
  - A variável `perto_da_porta` controla se o jogador está perto da porta.

## Observações

- Os scripts estão em `.txt` por questão de compatibilidade, mas podem ser copiados para arquivos `.gd` e usados diretamente no Godot 4.x.
- Para testar, é necessário criar cenas no Godot (Control ou Node2D) e adicionar os scripts aos respectivos nós.
- A ação de interação ("interagir") deve ser configurada no Input Map do Godot (ex: tecla E).
