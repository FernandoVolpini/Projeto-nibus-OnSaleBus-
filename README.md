### **Sistema de Gerenciamento de Viagens - Java POO**

**Descrição:**  
Aplicação de console em Java para gestão completa de uma empresa de transporte rodoviário, com:  
- ✈️ **Cadastro de cidades** (destinos)  
- 👥 **Gerenciamento de passageiros**  
- 🎫 **Venda, listagem e cancelamento de passagens**  
- 📊 **Relatórios de passageiros por cidade**  

**Funcionalidades Técnicas (Conforme Documento):**  
✔ **Classes Implementadas:**  
   - `Passageiro` (nome, CPF)  
   - `Cidade` (nome, estado)  
   - `Passagem` (com associação a `Passageiro` e `Cidade`, valor calculado)  
   - `GerenciadorDePassagens` (lógica de negócios)  

✔ **Princípios de POO Aplicados:**  
   - Encapsulamento (atributos privados + getters/setters)  
   - Herança (se houver classes como `PassagemPromocional`)  
   - Polimorfismo (métodos como `calcularValor()` sobrescritos)  

✔ **Estruturas de Dados:**  
   - `ArrayList` para armazenar cidades, passageiros e passagens  
   - `HashMap` para relatórios (ex: contagem de passageiros por cidade)  

✔ **Tratamento de Exceções:**  
   - Validação de CPF, dados vazios e duplicados  

✔ **Persistência:**  
   - Gravação/leitura em arquivos `.txt` ou `.dat` (serialização)  

**Como Executar:**  
1. Clone o repositório  
2. Compile com `javac`  
3. Execute a classe principal (`Main.java`)  

**Exemplo de Saída no Console:**  
```
[1] Cadastrar Cidade  
[2] Vender Passagem  
[3] Cancelar Passagem (por CPF)  
[4] Listar Passageiros por Cidade  
```  

**Requisitos Cumpridos:**  
✓ Menu interativo no console  
✓ Validações de entrada  
✓ Documentação no código (comentários Javadoc)  

**Tecnologias:**  
`Java 11+` | `Collections Framework` | `Serialização`  
