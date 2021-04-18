# Descomplicando o trabalhar para fora

Praticamente toda semana eu e o [Caffo] recebemos emails com dúvidas de pessoas que estão planejando ou começando a trabalhar com empresas no exterior. Normalmente eu tento responder rapidamente porém com a correria do trabalho e da vida pessoal nem sempre isso é possível.

Normalmente as perguntas são bem parecidas, mas mesmo fazendo um "copy and paste" acabo demorando para responder. Sei que isso é bem ruim para quem manda o email, mas até então era o melhor que eu podia fazer. Outro dia o [Caffo] me deu a ideia de escrever um FAQ/post sobre isso e resolvi que esse seria o meu presente de Natal para a comunidade de desenvolvedores.

Como esse artigo é de um desenvolvedor para outros desenvolvedores acho que não existe lugar melhor para publicar do que no [GitHub](http://github.com/tapajos/trabalhando_fora). Para fazer essa [página bonitinha](http://tapajos.me/trabalhando_fora) estamos usando o [DocumentUp](http://documentup.com/). Se quiser contribuir sugiro dar uma lida nas dicas de formatação.

Tentei responder as perguntas mais frequentes mas provavelmente muitas dúvidas foram esquecidas. Você pode me enviar suas [dúvidas](https://github.com/tapajos/trabalhando_fora/issues) e vou tentar responder o mais rápido possível.

## Disclaimer

Esse artigo foi escrito baseado na minha experiência trabalhando com exportação de software desde 2008 e de [outros colaboradores](https://github.com/tapajos/trabalhando_fora/graphs/contributors). As coisas mudam com uma certa frequência e não estou assumindo nenhum compromisso de manter esse artigo atualizado.

Eu não sou contador, não sou advogado tributarista e nem especialista em comércio exterior. Não tenho nenhuma responsabilidade por qualquer problema que você venha a ter. Minha recomendação é que você procure profissionais competentes e de sua confiança para te orientar.

## Contratação

Só existe uma regra: TENHA UM CONTRATO entre você e a empresa/pessoa de fora. Esse contrato é a forma de você comprovar a origem e a legalidade do dinheiro que você está recebendo.

## Impostos

O que você vai pagar de imposto vai depender da forma como você foi contratado, isto é, se foi via pessoa física ou jurídica. Não vou entrar na discussão da legalidade de você usar uma pessoa jurídica, sugiro que pesquise, consulte um bom advogado tributarista antes de tomar uma decisão. Não se esqueça de considerar os custos de contabilidade se você optar por abrir uma empresa.

### Pessoa Física
Vai pagar apenas o Imposto de Renda normal, de acordo com a tabela vigente. Nesse caso, você recebe o dinheiro da forma que for mais conveniente e deve declarar mensalmente no programa do Carnê Leão (que você encontra no Google / site da Receita Federal). Ele vai gerar um boleto para que você pague o IR convencional, todo mês, e no começo do ano, você poderá importar o relatório dele no programa de Declaração e Ajuste do IRPF.

Na prática, funciona da mesma forma que uma empresa CLT faria por você - exceto que eles fazem o pagamento à receita e descontam na sua folha de pagamento, mas o valor do imposto é o mesmo. Vale citar que, ao contrário do que muita gente pensa, calcular 27.5% em cima do que vai ser recebido é **errado**, pois o imposto é crescente de acordo com os níveis - mas não muda de acordo com o quanto você recebe; faça a previsão correta no [Simulador de alíquota do IRPF oficial](http://www.receita.fazenda.gov.br/aplicacoes/atrjo/simulador/simulador.asp?tipoSimulador=M).

### Pessoa Jurídica
Nesse caso os impostos podem variar bastante de acordo com o tipo da sua empresa e a sua localização. Se a sua empresa for cadastrada no Simples você irá pagar os impostos como se tivesse prestando serviço no Brasil. Caso sua empresa seja de Lucro Presumido você pode usufruir da isenção de PIS e Cofins existente para serviços de exportação de software conforme [IN-RFB 1911 Art. 21 Inciso II de 11/10/2019](http://normas.receita.fazenda.gov.br/sijut2consulta/link.action?idAto=104314&visao=compilado).

Dependendo do seu município você ainda pode contar com isenção de ISS. Porém, para ter essa isenção, é necessário que exista no seu contrato uma cláusula de não verificação em território nacional.

## PayPal

Muita gente me pergunta sobre receber via PayPal e a minha recomendação é para que você **não** faça isso. O PayPal não é banco e possui suas próprias regras e estas não são muito claras. Resista a tentação da simplicidade deles, você pode ter várias dores de cabeça.

Conheço duas pessoas que tiveram as contas canceladas (suspeita de atividades ilegais) e que nunca conseguiram recuperar o dinheiro que estava lá. Uma delas tinha 15 mil dólares na conta, já enviou fax com contrato, uma infinidade de documentos e até hoje não teve nenhuma resposta deles.

## Recebendo pagamentos com a Husky

A [Husky](https://husky.io/?utm_source=remote) é um aplicativo que elimina a burocracia a um preço justo, o que é um benefício interessante em um mercado que sempre cobra os clientes com taxas variáveis.

O suporte é um diferencial. O atendimento é muito rápido, sempre feito por chat dentro do próprio aplicativo, e se você precisar eles até te ligam para resolver seu problema. O ponto é que é difícil acontecer algum problema, mas se acontecer, eles vão resolver pra você. A empresa foi criada por dois programadores brasileiros que trabalhavam remoto e que ficaram indignados com a dificuldade de receber os pagamentos. Essa experiência pessoal deles se traduz na experiência oferecida pelo serviço.

Em relação às taxas, a Husky chega a ser 3x mais barata que Paypal e bancos em geral: 4% do câmbio comercial. O grande diferencial aqui é que à medida que você indica o serviço para outras pessoas, a taxa vai diminuindo ainda mais. É possível não pagar nada (zero, de verdade, no câmbio comercial).

Diferentemente das outras opções digitais, ela suporta pessoa jurídica facilmente e não tem limites de transação. Receber como pessoa jurídica é mais vantajoso porque você paga menos imposto de renda. Ao declarar o IR como Pessoa Física, você terá que pagar 27.5% de IR, enquanto que como PJ o imposto fica entre 6% a 17%, dependendo do CNAE da sua empresa.

Além disso, não é necessário para a empresa que vai te fazer o pagamento também ter cadastro na Husky, já que quando você completa o cadastro eles criam uma Conta Bancária Internacional em seu nome, permitindo que você utilize essa mesma conta para receber de qualquer lugar do mundo. Portanto para a empresa é apenas uma transferência bancária comum (Wire Transfer).

Outra característica útil é que a Husky pode depositar seu pagamento em qualquer banco aqui no Brasil. Isso permite que você continue utilizando a sua conta bancária atual.

#### Como usar a Husky

Você baixa o aplicativo e faz o cadastro. A Conta Bancária Internacional fica pronta na mesma hora, disponível lá no aplicativo, e inclusive por lá mesmo você pode avisar sobre a sua nova conta para a empresa que vai te pagar.

Se for uma plataforma internacional, basta alterar na plataforma pra sua conta da Husky.

Quando a transferência chega, você é notificado, e ela é automaticamente processada e enviada para sua conta no Brasil, já em Reais, eliminando a necessidade de "ligar para fechar o câmbio" ou qualquer outra preocupação. É um processo totalmente digital e transparente.

## Escolha do banco ou corretora

Essa é uma pergunta bastante recorrente e a resposta é que não existe um banco que seja maravilhoso e no início você vai ter bastante trabalho. Na prática são três coisas que fazem a escolha do banco ser importante: cotação do dólar, tarifa de operação e o processo.

Cada banco tem um procedimento totalmente diferente e você deve analisar qual que te atende melhor. No meu caso o mais importante é não precisar sair de casa, se eu puder fazer tudo de casa eu até aceito uma cotação ruim e/ou uma tarifa mais alta.

Outra forma de fazer a operação cambial, que possivelmente terá cotações e taxas mais atraentes do que as oferecidas pelos bancos comuns do mercado, é abrir uma conta em uma casa de câmbio.

Na Toptal a casa de câmbio preferida dos brasileiros é a B&T. Após a abertura da conta eles te darão os dados necessários para que você repasse ao seu cliente para o envio da wire transfer. A partir daí, em um dia útil ou dois a casa de câmbio receberá a quantia e te avisa, por Skype, do recebimento da mesma. Você pode aguardar o melhor dia/momento para fechar a operação, dado que o câmbio que te oferecem vai flutuar no decorrer do dia. A taxa que a B&T tem cobrado é um valor fixo em dólares + um pequeno spread. A partir do fechamento da operação, se este for feito até o meio-dia (horário em que o mercado de câmbio faz uma pausa, até as 13h30), o valor é creditado na conta-corrente da sua PJ no mesmo dia. Caso o câmbio seja feito durante a tarde (até as 15h30), o crédito ocorre no próximo dia útil.

Eu ([igorsantos07]) tentei migrar para a MultiMoney, que me foi indicada por outro toptaler como sendo mais em conta. No entanto, a economia saiu pela culatra. Eles cobram uma taxa fixa levemente maior que a da B&T, mas o spread é ainda mais reduzido (menos de 1%), mas o atendimento é bem... complicado. O recebimento das wires levava pelo menos dois dias, e tanto lidando com o pessoal da agência de Blumenau quanto com a sede a comunicação era falha. Por fim, tive problemas em ambas as agências para pedir a [isenção de ISS](#impostos), sendo que na sede eles se recusaram e passaram por cima de mim, efetuando o câmbio mesmo sem a isenção. A lição de moral é clássica: às vezes, o barato sai caro.

**Atenção**, não adianta pedir à sua empresa para fazer a Wire transfer em reais, a operação de câmbio será necessária para a liberação da quantia transferida.

## O fluxo de recebimento

1. Envio da invoice (ver detalhes abaixo)
2. Recebimento da Wire
3. Contratação do câmbio (fechamento de câmbio)
4. Emissão da nota fiscal (no caso de PJ)
5. Envio das informações do Siscoserv
6. Envio da nota fiscal e do boleto de câmbio para o contador (no caso de PJ)

## Nota Fiscal (no caso de PJ)

O processo de emissão da nota fiscal é bem parecido com o da prestação de serviços para o Brasil. O único detalhe é que ela deve ser emitida no dia do fechamento de contrato de câmbio e com o valor creditado em reais na conta corrente da empresa. Você deve consultar o seu contador para saber os detalhes da emissão da nota.

A nota fiscal não tem nenhum valor para a empresa de fora, não há necessidade de enviá-la.

## Invoice

A [invoice](http://en.wikipedia.org/wiki/Invoice) é um tipo de fatura. Não existe nenhum mistério em gerar invoices, o único detalhe é que a numeração deverá ser única.

Você pode usar até o Word para gerar esse documento. Eu utilizo e recomendo o [Blinksale](http://www.blinksale.com/).


[caffo]: http://twitter.com/caffo
[igorsantos07]: http://igorsantos.com.br

