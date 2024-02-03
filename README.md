# ESTRUTURA DE UMA API RESTful EM PHP PURO

## :rocket: Tecnologias utilizadas

<li>PHP 7.4</li>
<li>MVC - padrão de projeto </li>

## :loudspeaker: Apresentação

> Este repositório é um projeto com uma estrutura padrão para a criação de APIs RESTful com PHP.

## ⚙ Features

- [x] Não utiliza frameworks, apenas PHP puro.


  ```bash
  #Instalando as dependências
  $ composer install      
  ```

### Configurando:

- OBS: Todas as **configurações** estão nos arquivos **/config.php** e **/environment.php**.

- No arquivo **/environment.php**, comente uma das duas definições da constante **ENVIRONMENT** de acordo com a sua necessidade

- As configurações de Banco de Dados e URL estão no arquivo **/config.php**, tanto para **ENVIRONMENT=development** e **ENVIRONMENT=production**:

```php
    define('BASE_URL', 'http://127.0.0.1/struct-api-restful-php/');

    $config['dbname'] = 'project-struct-api-restful'; //banco de exemplo
    $config['host'] = '127.0.0.1'; //ou 'localhost'
    $config['dbuser'] = 'root'; //login BD exemplo
    $config['dbpass'] = ''; //senha BD exemplo
```

- É importante configurar corretamente a constante *BASE_URL* dentro do **config.php**:
  
  > define('BASE_URL', 'http://127.0.0.1/struct-api-restful-php/'); //EXEMPLO 

<table align="center">
  <tr>
    <td align="center">
      <a href="#">
        <img src="https://avatars.githubusercontent.com/u/109317442?v=4" width="160px;" alt="Erick Rodrigues"/><br>
        <sub>
          <b>Erick Rodrigues</b>
        </sub>
      </a>
    </td>
  </tr>
</table>
