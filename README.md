# Tradução do Laravel 5.x em Português do Brasil

## Instalação

### 1 - Clonar o projeto na pasta `resources/lang/`
> substituir {TAG} pela versão do laravel: **5.1**
```bash
$ cd resources/lang/
$ git clone -b {TAG} https://github.com/wendtecnologia/laravel-pt-br.git ./pt-br
```

### 2 - Configurar o Framework para utilizar a linguagem como Default
```php
  // Linha 55 do arquivo config/app.php
  'locale' => 'pt-br',
```

### 3 - (Opcional) Para versionar no seu projeto
Você pode remover o diretório .git para versionar os arquivos deste projeto no seu repositório.

```bash
$ rm -rf pt-br/.git/
```

## Autores
Essa tradução foi atualizada a partir do conteúdo disponibilizado por:
  * **[Bruno Monteiro](https://github.com/bmonteirog)**:         https://github.com/bmonteirog/laravel-5.1-pt-br-localization

## Contribuidores
A lista completa pode ser visualizada em [CONTRIBUTORS.md](CONTRIBUTORS.md)
