# Identificando ameaças

Parte impressindível da segurança é conseguir visualizar as ameaças ao longo do processo; mas partindo do princípio, o que pode ser entendido como ameaça?
Uma ameaça é qualquer evento, pessoa, ação ou objeto que possa representar um risco ou perigo para a segurança de um sistema, seja ele físico (como um prédio), digital (como uma rede) ou até mesmo um sistema social (como uma comunidade ou organização).

Para compreender sobre o panorama de ameaças o mais indicado é conhecer as técnicas e táticas, acesse o [MITRE ATT&CK®](https://attack.mitre.org/)
É na verdade uma base de conhecimento acessível globalmente de táticas e técnicas adversárias baseadas no mundo real que sofre constantes atualizações. Não é necessário que decore todas as táticas e passos, mas é importante analiser todo o conteúdo para, posteriormente, verificar onde o seu produto poderia se encaixar em alguma tentativa maliciosa, formas de explorar, afins. 

Adicionalmente, vai além do escopo do time do AppSec --nada de novo por aqui--, mas vale o conhecimento. A busca por ameaças correlacionadas à fraudes pode ser obtida através de insights do próprio cotidiano de seu produto. Por exemplo, você têm se atualizado sobre os últimos golpes e falhas do produto que está inserido? Para expandir os horizontes, vamos rascunhar um exemplo.

**Produto: Seguradora**
**Fraudes na mídia:** 
- Fracionamento de desespesas de saúde para recebimento indevido de reembolso;
- Entrega de veículo segurado a um terceiro malicioso com o objetivo de dar fim ao bem;
- Receber indenização de bens não existentes em residência ou empresa.

E claro, muitos outros. Então sempre recomendo a busca de matérias correlacionando a fraude com produtos de forma genérica, então se você está dentro de um ambiente e há uma nova funcionalidade sendo criada, ela poderia abrir brechas a um nicho explorado atualmente por fraudadores? Ou facilitaria a forma de explorar? 
A necessidade intrínsica de um AppSec é se atualizar não só sobre tecnologias, mas também o cotidiano nacional e até movimentações internacionais. Essas buscas podem vir através de assinaturas de newsletter, matérias esporádicas, podcasts de notícias voltados para segurança e afins. 

Para uma modelagem no geral, eu sugiro que tente reduzir a análise de ameaças para até 3 ou 4 personas. 
1. Interceptação da comunicação
2. Alteração (edição ou remoção) de informações
3. Exploração de configurações falhas (DOS/DOW/DDOS)
4. Uso indevido/furto de credenciais de terceiros.

Claro, os atores de ameaça poderiam ser além desses, mas varia de acordo com o seu dia a dia. 
