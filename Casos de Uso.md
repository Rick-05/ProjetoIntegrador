# Casos de Uso

Os casos de uso são utilizados para especificar as tarefas e os atores envolvidos nelas. Será utilizado futuramente para especificar os requisitos funcionais e não funcionais do projeto.

## Tabela de Conteúdos

- [Casos de Uso](#casos-de-uso)
  - [UC-01 Visualizar Página Inicial](#uc-03-visualizar-página-inicial)

## [Casos de Uso](#tabela-de-conteúdos)

![Diagrama de Casos de Uso]

### [[UC-01] Visualizar Página Inicial](#tabela-de-conteúdos)

![Diagrama de Atividades - UC-03]

<table>
  <tr>
    <th>Nome</th>
    <td>Visualizar Página Inicial</td>
  </tr>
  <tr>
    <th>ID</th>
    <td>UC-03</td>
  </tr>
  <tr>
    <th>Atores</th>
    <td>
      <ul>
        <li>Usuário</li>
        <li>Sistema</li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Descrição</th>
    <td>O caso de uso descreve a interação do usuário com a página inicial do sistema após o login.</td>
  </tr>
  <tr>
    <th>Fluxo Principal</th>
    <td>
      <ol>
        <li>Usuário acessa a página inicial.</li>
        <li>O sistema verifica se o usuário está logado.</li>
        <li>Se o usuário está logado, a página inicial exibe o crachá mais recente do usuário.</li>
      </ol>
  </tr>
  <tr>
    <th>Fluxo Alternativo 4-a: Informações Inválidas</th>
    <td>
      <ol>
        <li>Se o usuário não está logado, o sistema mostra a mensagem “Para salvar os seus crachás, faça login”.</li>
      </ol>
    </td>
  </tr>
  <tr>
    <th>Pré-Condições</th>
    <td>
      <ul>
        <li>O usuário possui uma conta registrada no sistema</li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Pós-Condições</th>
    <td>
      <ul>
        <li>O usuário visualiza o conteúdo da página inicial.</li>
        <li>O usuário pode acessar as funcionalidades da aplicação.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Requisitos Funcionais</th>
    <td><ul>
      <li><a href="/Requisitos.md#rf-v07-p%C3%A1gina-inicial">[RF-V07] Página Inicial</a></li>
    </ul></td>
  </tr>
  <tr>
    <th>Requisitos Não Funcionais</th>
    <td></td>
  </tr>
  <tr>
    <th>Casos de Uso Relacionados</th>
    <td>
      <ul>
        <li><a href="#uc-02-realizar-login">[UC-02] Realizar Login</a></li>
        <li><a href="#uc-04-criar-crachas">[UC-04] Criar Crachás</a></li>
        <li><a href="#uc-05-visualizar-crachas">[UC-05] Visualizar Crachás</a></li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Notas</th>
    <td>
      <ul>
        <li>Certificar-se de uma navegação intuitiva e fácil acesso a funcionalidades importantes a partir da página inicial.</li>
      </ul>
    </td>
  </tr>
</table>
