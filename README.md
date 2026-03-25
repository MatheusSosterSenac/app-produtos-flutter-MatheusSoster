# app-produtos-flutter-MatheusSoster

Aluno: Matheus henrique Soster
Turma: ADS 5 Fase 2026

====== Fluxo do Projeto ======

1.Tela inicial (Lista de Produtos)
- Exibe a lista de produtos cadastrados
- Botão + abre a tela de cadastro
  
2. Tela de Cadastro
- Usuário insere:
Nome
Preço

- Ao clicar em Salvar:
Retorna para a lista (Navigator.pop)
Produto é adicionado automaticamente

3. Tela de Detalhes
- Ao clicar em um produto da lista:
Abre a tela de detalhes (Navigator.push)
- Exibe:
Nome
Preço formatado (R$ 0,00)

4. Retorno
Botão voltar retorna à lista mantendo os dados

================================
====== Como Executar ======

1. cd app_produtos
2. flutter pub get
3. flutter run

================================
