# 1. História de Usuário

A Tabela 3 a seguir contém as Histórias de Usuárias elicitadas. 

<table>
    <thead>
        <tr style="background-color: purple; color: white" >
            <th style="border-style:solid;border-width:1px;text-align:center">ID</th>
            <th style="border-style:solid;border-width:1px;text-align:center">História de Usuário</th>
            <th style="border-style:solid;border-width:1px;text-align:center">Critérios de aceitação</th>
            <th style="border-style:solid;border-width:1px;text-align:center">Prioridade</th>
            <th style="border-style:solid;border-width:1px;text-align:center">RF/RNF relacionado</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <span id="ustory-01"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US01</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Eu, como usuário regular, quero acessar os meus medicamentos</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol><li>Na tela inicial do aplicativo deve ficar listados todos os medicamentos cadastrados pelo usuário, sendo que cada um ao ser clicado deve ser levado á sua tela específica.</li><li> Caso não tenha nenhum medicamento cadastrado, deverá ter um texto alertando na tela.</li><li>Ao início da tela, deve ter um botão que possibilite o usuário adicionar mais medicamentos.</li></ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF02</td>
        </tr>
        <tr>
            <span id="ustory-01"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US02</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Eu, como usuário regular, quero adicionar novos medicamentos ao aplicativo</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol><li>Ao clicar no botão de adicionar medicamento da US01, o usuário deverá ser redirecionado á esta nova tela para o cadastro.</li><li>Deverão ter campos para o usuário informar: Nome do medicamento; Tratamento (para que o remédio é); Dosagem; Horários de consumo; Duração do tratamento (Dia X até Dia Y)</li></ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"> Alta </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF01</td>
        </tr>
        <tr>
            <span id="ustory-01"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US03</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Eu,como usuário regular, quero acessar um medicamento específico</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol><li>Selecionando um medicamento listado na tela da US01, o usuário deverá ser redirecionado á esta tela com as informações do medicamento selecionado</li><li>Deverão ser exibidas nessa tela todas as informações cadastradas para este medicamento</li><li>Abaixo das informções, deve ter uma "linha do tempo" do medicamento, mostrando cada dosagem que foi ou deixou de ser tomada nos dias, no formato de "carrossel" onde o usuário podera deslizar para os lados para passar os dias</li><li>Ao fim desta tela, deverá ter um botão de "Editar" e um botão de "Excluir"</li></ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF03</td>
        </tr>
        <tr>
            <span id="ustory-01"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US04</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Eu,como usuário regular, quero editar as informações de um medicamento</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol><li>Ao clicar no botão de "Editar" da US03, o usuário deverá ser redirecionado á esta tela</li><li>Esta tela será estruturada similar á tela de cadastro de medicamento (US02), porém com os campos ja preenchidos com as informações do medicamento em questão, permitindo também que o usuário realize alterações.</li></ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Média</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF07</td>
        </tr>
        <tr>
            <span id="ustory-01"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US05</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Eu,como usuário regular, quero remover um medicamento</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol><li>Ao clicar no botão de "Excluir" da US03, uma janela de confirmação deverá surgir na tela do usuário, na qual ele terá uma opção para confirmar a exclusão ou cancelá-la.</li></ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Média</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF08</td>
        </tr>
        <tr>
            <span id="ustory-01"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US06</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Eu,como usuário regular, quero ver um histórico de meus medicamentos</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol><li>Uma tela que deverá conter duas seções expansivas: "Medicamentos Finalizados" e "Em Andamento/Futuros"</li><li>O controle de qual medicamento vai para cada seção será a partir da data final do tratamento informada no cadastro, então os que ja tiverem passado dessa data final irão para "Medicamentos Finalizados" e os que ainda não chegaram ao final irão para "Em Andamento/Futuros".</li><li>Em cada seção, os medicamentos deverão ficar listados de modo que o usuário consiga ver: o nome do medicamento; sua data de inicio e fim; doses perdidas</li></ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Baixa</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF04</td>
        </tr>
        <tr>
            <span id="ustory-01"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US07</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Eu,como usuário regular, quero visão ampla dos medicamentos a serem tomados</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol><li>Uma tela no formato de um calendário mensal, que o usuário consiga não só ver o mês atual como também ver passados e futuros.</li><li>Cada campo do calendário representará o dia indicado e deverá exibir o nome dos medicamentos a serem tomados naquele dia, além que deve ser algo clicável para o usuário conseguir acessar as informações específicas daquele dia.</li></ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF05</td>
        </tr>
        <tr>
            <span id="ustory-01"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US08</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Eu,como usuário regular, quero acompanhar os medicamentos a serem tomados em um dia</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol><li>Ao clicar no campo de um dia no calendário (US07), esta tela deverá ser aberta</li><li>Tela que deverá informar o dia, mês e ano em questão, além de uma listagem dos medicamentos programados para aquele dia.</li><li>Os medicamentos devem ser listados (em ordem de horário de consumo) de modo que cada um informe: nome do medicamento; dia "X" de tratamento; dosagem; horário(s) de consumo; checkbox para o usuário marcar caso ja tenha consumido</li><li>Caso o usuário marque a checkbox, o medicamento deve ser "riscado" tanto nesta tela quanto em seu campo na US07</li></ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF06</td>
        </tr>
</table>

<div style="text-align: center">
<p>Tabela 3: História de Usuário</p>
</div>

## 5. Referências bibliográficas
