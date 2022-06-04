# Teste de Engenharia de Software - TPSI - 2021/22

1. Crie um repositório no GitHub com o seguinte formato <NR_ALUNO>-ESW-TESTE-1, o repositório deve ser privado.
Todos os exercícios seguintes devem ser feitos dentro deste repositório.

---

2. Crie um ficheiro `README.MD` com o conteúdo abaixo:

	```
	# Teste de Engenharia de Sofware

	- **Aluno:** *NR_ALUNO*
	- **Nome:**  *NOME_ALUNO*
	- **Data:**  *DIA_DE_HOJE*
	```

  - **2.1.** Crie um *commit* com esse ficheiro no *branch* "master" com a mensagem `#2 – Add README.MD`, faça também o *push* para o repositório remoto.

---

3. Crie um novo *branch* com o nome "feat/ex3" com base na versão mais recente do "master".

  - **3.1.** Copie a pasta `ex3` para o seu repositório, crie um commit com o texto `#3 – Add ex3 files` e envie para o repositório remoto.

  - **3.2.** O ficheiro `CalculatorAPI.java` não tem comentários *JavaDoc*, adicione-os ao ficheiro utilizando as *tags* que considerar relevantes.

    - Crie um *commit* com o texto `#3 - Add Javadoc to CalculatorAPI.java`
    - Envie o *commit* para o repositório remoto.

  - **3.3.** Crie testes unitários para cada método da classe `CalculatorAPI`.

    - Crie um *commit* com o texto `#3 - Add JUnit tests to CalculatorAPI.java`
    - Envie o *commit* para o repositório remoto.

  - **3.4.** Inclua as alterações do *branch* "feat/ex3" no "master" (merge).

    - Faça push de ambos os *branches* para o repositório remoto **(Não apague o branch "feat/ex3")**

---

4. Crie um novo *branch* com o nome "feat/ex4" com base na versão mais recente do "master".

  - **4.1.** Crie um novo projecto maven com as seguintes caracteristicas:
    - **Group ID:** pt.esgts.esw
    - **Artifact ID:** ex4
    - Crie um *commit* com o texto `#4 - Create project`
    - Envie o *commit* para o repositório remoto.


  - **4.2.** Crie uma aplicação para gerar palavras passe, deve usar uma *library* externa para o efeito
    - Pode consultar mais info sobre a bibioteca recomendada [aqui](https://github.com/bruno-esgts/password-generator-lib)
    - Crie um *commit* com o texto `#4 - Using password generation library`
    - Envie o *commit* para o repositório remoto.

