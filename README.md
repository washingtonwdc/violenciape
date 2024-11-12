# Mapa de Violência do Estado de Pernambuco

Este projeto é uma integração de um dashboard do Power BI que exibe um mapa de violência do estado de Pernambuco.

## Estrutura do Projeto

O projeto consiste em um único arquivo HTML que contém o código necessário para exibir o dashboard do Power BI.

### Arquivo principal

- `index.html`: Contém a estrutura HTML e o estilo CSS para exibir o dashboard.

## Como Visualizar

Para visualizar o dashboard, basta abrir o arquivo `index.html` em um navegador web. O dashboard será carregado em um iframe dentro da página.

## Exemplo de Código

```html
<!DOCTYPE html>
<html>
<head>
    <title>Mapa de violência do estado de Pernambuco</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        h1 {
            text-align: center;
            color: #333;
        }
        .dashboard-frame {
            border: none;
            width: 100%;
            height: 600px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Power BI Dashboard Integration</h1>
        <iframe 
            class="dashboard-frame" 
            src="https://app.powerbi.com/view?r=eyJrIjoiNTQ4Y2Y1ZDgtYWJmYi00ODZjLWJhNmYtNDg0NDMxNWYwNjNiIiwidCI6Ijk3ZjdhNzBhLTQwMTEtNDU0NC04MDRmLWQwNjcxZmMyYWFlOSIsImMiOjl9" 
            title="Power BI Dashboard"
            allowFullScreen>
        </iframe>
    </div>
</body>
</html>
