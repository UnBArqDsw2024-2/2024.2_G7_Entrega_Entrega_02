# HungryHub

## 📃 Informações acadêmicas

**Código da Disciplina**: FGA0208<br>
**Número do Grupo**: 07<br>
**Entrega**: 02<br>

## 👥 Alunos

| Matrícula   | Aluno | 📷 |
|-------------|---------------------------------------------------------|-------------|
| 221034973   | [Bruno Cunha Vasconcelos de Araújo](https://github.com/brunocva) | <img width="100" src="https://github.com/brunocva.png" style="border-radius: 50px"/> |
| 190105071   | [Davi Gonçalves Akegawa Pierre](https://github.com/DaviPierre) | <img width="100" src="https://github.com/DaviPierre.png" style="border-radius: 50px"/> |
| 221022275   | [Felipe Amorim de Araújo](https://github.com/lipeaaraujo) | <img width="100" src="https://github.com/lipeaaraujo.png" style="border-radius: 50px"/> |
| 221022570   | [Gabryel Nicolas Soares de Sousa](https://github.com/gabryelns) | <img width="100" src="https://github.com/gabryelns.png" style="border-radius: 50px"/> |
| 221021984   | [Guilherme Silva Dutra](https://github.com/GuiDutra21) | <img width="100" src="https://github.com/GuiDutra21.png" style="border-radius: 50px"/> |
| 211061805   | [Guilherme Westphall de Queiroz](https://github.com/west7) | <img width="100" src="https://github.com/west7.png" style="border-radius: 50px"/> |
| 221022041   | [Júlio Roberto da Silva Neto](https://github.com/JulioR2022) | <img width="100" src="https://github.com/JulioR2022.png" style="border-radius: 50px"/> |
| 202046229   | [Kallyne Macedo Passos](https://github.com/kalipassos) | <img width="100" src="https://github.com/kalipassos.png" style="border-radius: 50px"/> |
| 232014727   | [Kauan de Torres Eiras](https://github.com/kauaneiras) | <img width="100" src="https://github.com/kauaneiras.png" style="border-radius: 50px"/> |
| 200022199   | [Leonardo Sobrinho de Aguiar](https://github.com/Leonardo0o0) | <img width="100" src="https://github.com/Leonardo0o0.png" style="border-radius: 50px"/> |
| 221022088   | [Lucas Martins Gabriel](https://github.com/martinsglucas) | <img width="100" src="https://github.com/martinsglucas.png" style="border-radius: 50px"/> |
| 211062437   | [Raquel Ferreira Andrade](https://github.com/raquel-andrade) | <img width="100" src="https://github.com/raquel-andrade.png" style="border-radius: 50px"/> |
| 231032121   | [Wolfgang Friedrich Stein](https://github.com/Wolffstein) | <img width="100" src="https://github.com/Wolffstein.png" style="border-radius: 50px"/> |

## 💡 Sobre 
O HungryHub é um aplicativo de entrega/delivery de comida, lanches e bebidas, que oferece acessibilidade e conveniência para clientes, entregadores e estabelecimentos por meio de uma plataforma simples e interativa com uma lógistica de entrega rápida e eficiente.

Essa documentação visa armazenar e documentar todos os artefatos produzidos e resultados do desenvolvimento da primeira entrega do grupo 07 da disciplina de Arquitetura e Desenho de Software, ministrada pela professora Milene Serrano no segundo semestre letivo de 2024 na Universidade de Brasília (UnB). A segunda entrega se refere ao módulo **Modelagem** das diretrizes do projeto incluindo aos focos de **Modelagem Estática** & **Modelagem Dinâmica** & **Modelagem Organizacional/Casos de Uso**.

## Screenshots da Primeira Entrega
Adicione 2 ou mais screenshots em termos de artefatos realizados na entrega.

<center>



</center>

## Há algo a ser executado?

(X) SIM

( ) NÃO

O ambiente de desenvolvimento do projeto foi configurado e pode ser encontrado na branch [dev](https://github.com/UnBArqDsw2024-2/2024.2_G7_Entrega_Entrega_02/tree/dev) do repositório. Na branch foi criado um documento para auxiliar a configurar o ambiente de desenvolvimento e executar o projeto.

### Back

1. Entre na pasta do projeto:

```bash
    cd HungryHub/HungryHub.2024.2-Back
```

2. Crie um ambiente virtual com o comando:

```bash
    python3 -m venv ambv
```

3. Ative o ambiente virtual com o comando:

```bash
    source ambv/bin/activate #linux
    .\ambv\Scripts\activate #windows
``` 
4. Instale as dependências do projeto com o comando:

```bash
    pip install -r requirements.txt
```
5. No primeiro acesso execute o comando:

```bash
    python manage.py migrate
```

6. Execute a aplicação com o comando:

```bash
    python manage.py runserver
```

Os endpoints disponíveis estão em:
`localhost:8000/api/swagger`

### Front

1. Entre na pasta do projeto:
   
```bash
    cd HungryHub/HungryHub.2024.2-Front/hungryhub
```

2. Instale as dependências do projeto com o comando:

```bash
    npm install
```

3. Para executar o frontend com o expo basta executar o seguinte comando:

```bash
    npx expo start
```
Após isso, basta escanear o QR Code com o aplicativo `Expo Go` no seu celular, rodar em um emulador ou até mesmo pelo navegador.

## Histórico de Versão

| Versão | Data da alteração | Comentário | Autor(es) | Revisor(es) | Data de revisão |
| -- | -- | -- | -- | -- | -- |
| 1.0 | 13/11/2024 | Criação do documento | [Felipe Amorim de Araújo](https://github.com/lipeaaraujo) | | |
| 1.1 | 28/11/2024 | Adicionando elementos da entrega 2 | [Felipe Amorim de Araújo](https://github.com/lipeaaraujo) | | |
