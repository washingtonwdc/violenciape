# Mapa de Violência do Estado de Pernambuco

Este dashboard interativo do Power BI apresenta dados detalhados sobre a violência no estado de Pernambuco. Desenvolvido pela Secretaria de Defesa Social (SDS), o painel oferece uma visão abrangente sobre crimes contra a vida e o patrimônio, incluindo homicídios, feminicídios, estupro e violência doméstica.

## Metodologia de Coleta e Análise de Dados

Desde 15 de julho de 2020, a SDS disponibiliza dados criminais mensalmente para consulta pública. Os dados são organizados e consolidados pela Gerência Geral de Análise Criminal e Estatística (GGACE), garantindo qualidade e respeito à privacidade das vítimas. A metodologia segue as diretrizes da Lei de Acesso à Informação e da Lei Geral de Proteção de Dados.

Os dados são publicados de maneira preliminar até o 5º dia do mês subsequente e consolidados até o 15º. O dashboard permite filtros por sexo, idade e comparações históricas, facilitando a análise por pesquisadores e gestores públicos.

## Uso do Dashboard

Este painel é uma ferramenta essencial para entender as tendências de violência no estado. Ele suporta a formulação de políticas públicas e estratégias de segurança, como o programa "Juntos pela Segurança", que visa reduzir os índices de violência até 2026.

<iframe 
    class="dashboard-frame" 
    src="https://app.powerbi.com/view?r=eyJrIjoiNTQ4Y2Y1ZDgtYWJmYi00ODZjLWJhNmYtNDg0NDMxNWYwNjNiIiwidCI6Ijk3ZjdhNzBhLTQwMTEtNDU0NC04MDRmLWQwNjcxZmMyYWFlOSIsImMiOjl9" 
    title="Dashboard do Power BI de Violência"
    allowfullscreen>
</iframe>

<style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        background-color: #f4f4f4;
        color: #333;
    }
    .container {
        width: 90%;
        max-width: 1200px;
        margin: 20px auto;
        padding: 20px;
        background-color: #fff;
        box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    }
    h1, h2 {
        text-align: center;
        color: #333;
        margin-bottom: 20px;
    }
    p {
        line-height: 1.6;
        margin-bottom: 20px;
    }
    .dashboard-frame {
        border: none;
        width: 100%;
        height: 600px;
        margin-top: 20px;
    }
    @media (max-width: 768px) {
        .dashboard-frame {
            height: 400px;
        }
    }
    .footer {
        text-align: center;
        padding: 10px;
        background-color: #333;
        color: #fff;
        margin-top: 20px;
    }
</style>