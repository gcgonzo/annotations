# Annotations Spring Boot

  - **@Entity**  - Significa que uma classe é uma entidade (ou seja, ela é uma tabela no banco de dados).É a nossa classe principal, onde ficará os atributos dos objetos, construtores, getters e setters. 
  - **@Table(name = "TB_TIPO")** - É a declaração de uma tabela(informando o nome).
  - **@Id** - Declara o id de uma classe. **@GeneratedValue(strategy = GenerationType.AUTO)** - Gera um id automaticamente.
  - **@NotBlank** - Informa que um atributo não pode ser nulo.
  - **@Lob** - Permite textos muito longos.
  - **@Autowired** - Realiza uma injeção de dependências(sendo usado no repository).
  
