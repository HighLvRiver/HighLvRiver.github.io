---
layout: post
title:  "스팀잇에 대한 기본 이해 & 스팀잇의 철학"
date:   2018-03-07 23:00:00
categories: Steemit
---

# 스팀잇

## 들어가기에 앞서...
### 비트코인, 이더리움은 들어는 봤는데...스팀? 그 차이가 뭐야?
이 자료는 스팀에 대한 이야기를 주로 다루는 게 목적이기 때문에, 비트코인과 블록체인에 대해서는 심층적으로 다루진 않을 생각입니다. 다만, 비트코인과 이더리움, 스팀 각강의 차이에 대해서는 이해하고 넘어갈 필요는 있습니다.   

여러 차이가 있겠지만, 가장 핵심적인 차이는 바로 채굴 방식의 차이입니다. 가장 대표적인 비트코인의 경우 PoW(Proof of Work)라는 채굴 방식을 사용합니다. PoW는 작업증명 방식으로 "Proof of work" 열심히 일한만큼 보상받는다. 라는 약자입니다. 말 그대로 컴퓨터의 연산력으로 코인을 얻는 방식입니다. 더 좋은 컴퓨터, 더 좋은 채굴기를 보유하면 코인을 채굴할 수 있는 속도도 더 빨라지게 되는 방식입니다. PoW는 연산 문제를 계속 풀어야 함으로 고 사양 GPU로 많은 전력을 사용해서 많은 돈과 많은 전력소비가 들어가 규모의 경제가 필요합니다. 때문에 큰 자본이 있으면 얼마든지 채굴시장을 좌지우지 할 수 있습니다. 이미 비트코인은 가정용PC를 넘고 GPU를 넘어 ASIC채굴기로 채굴을 하여야만 채굴이 되는, 채굴이 가장 어려운 가상화폐입니다. 계속 채굴이 되다 보면 가치는 떨어질 테지만 비트코인은 총 수량이 정해져 있기때문에 다른 코인에 비해 가치가 많이 하락되지는 않을 예상입니다. 하지만 다른 가상화폐들은 총 수량이 정해져 있지 않고 PoW 채굴방식을 고집하는 가상화폐들이 있습니다. 예를 들어 똑같은 물건을 계속 찍어나가면 그 물건에 대한 가치는 하락하는 것처럼 가상화폐도 그렇게 될 수 있다는 말입니다. 하지만 이런 리스크를 감안한 가상화폐가 있습니다. 바로 이더리움입니다. 이 이야기는 아래 PoS의 대표 가상화폐에서 이어 가보겠습니다.

PoS는 지분증명 방식으로 "Proof of stake" 가지고 있는 만큼 보상한다. 라는 약자입니다. 말 그대로 PoS로 채굴되는 가상화폐를 보유하고 있으면 보유한 지분에 대한 이자의 개념으로 보상이 지급되는 방식입니다. 많은 수량의 가상화폐를 보유할수록 더 많은 보상이 지급이 됩니다. 즉, 특정 개수의 코인을 적금 들듯이 묶어두면 그만큼의 코인수익이 이자처럼 발생합니다. PoS 채굴 방식은 별도의 채굴기가 필요하지 않기 때문에 에너지 소비가 낮습니다. PoS 채굴의 가장 대표적인 가상화폐는 이더리움입니다. 이 문장을 읽고 많은 분들은 "왜 이더리움이 PoS라는 거야?" 라고 반박하실 수 있습니다. 이더리움은 개발시부터 PoS를 기획하고 개발된 가상화폐입니다. 현재의 이더리움은 PoS로 가기위한 베타 버전이라고 생각 하시면 쉽습니다. 처음 이더리움이 PoW로 채굴을 할 수 있게 한 이유는 대중성입니다. 이더리움을 알리고 거래를 할 수 있도록 PoW방식으로 진행이 되었습니다. 하지만 이더리움은 정해진 수량이 없기에 계속 PoW로 채굴을 하면 가치가 낮아진다는 리스크가 있어 현재 PoS로 가는 첫번째 하드포크를 진행하여 성공하였습니다. 에너지 효율 면에선 PoW 방식보다 뛰어나지만 블록의 최종 확인까지 여러 단계의 확인이 필요하며 거래 속도 저하됩니다.

이 두 가지 방식에 여전히 존재하는 문제점들을 보완하기 위한 방식이 바로 DPoS(Delegated Proof of Stake)입니다. 스팀이 바로 DPoS 방식을 사용하고 있습니다. DPoS 네트워크는 구성하는 모든 노드들의 투표 결과로 정한 ‘상위 노드’에게 권한을 위임하여 일종의 대표자가 되는 것입니다. PoS의 경우 일정 지분을 소유한 모든 노드에게 블록 생성 권한이 주어지기에 오랜 시간이 필요하지만 DPoS의 경우 상위 노드라는 비교적 적은 숫자로 인해 합의 시간과 비용을 줄일 수 있습니다. DPoS 방식은 PoW와 PoS보다 빠른 방식으로 블록을 생성할 수 있지만 정치와 마찬가지로 소수의 대표자가 결정하기 때문에 투표가 중요한 요소입니다. 투표의 경우 본인이 소유한 지분의 권한을 대표자에게 위임하는 것이라고 생각하면 됩니다.

신속한 블록 생성 시간뿐만 아니라 DPoS 방식은 대표자들끼리의 경쟁을 통해 비트쉐어 및 비트쉐어 커뮤니티에 더 많은 기여를 유도합니다. 기여를 많이 할수록 대표자가 될 가능성이 높아지기 때문이죠. 이와 같은 시스템의 대표적인 예는 EOS, Steemit 입니다. EOS의 경우 21명의 대표자가 있으며 스팀잇은 20명의 대표자가 존재합니다.

현재 DPoS 방식도 투표인원이 적을 경우 독점이라는 형태가 될 수 있다는 등의 여러 단점이 존재하지만 기존의 가상화폐 시장이 그래왔듯이 개선 혹은 더욱 효과적인 방식의 출현이 빠른 속도로 진행될 것으로 판단됩니다.

### 근데 왜 스팀잇이 요즘 화두?

스팀잇이 점점 화두로 떠오르는 이유는 블록체인 기반의 가상화폐를 실제 서비스에 적용해서 그 생태계가 정상적으로 운영될 수 있음을 증명한 첫번째 사례이기 때문입니다. 스팀잇은 광고 하나 없이 자본을 조달해가면서 커뮤니티 기여자들에게 보상을 지급하고 있습니다.

### 스팀(STEEM)? 스팀달러(SBD)?
스팀잇에 대한 설명을 하기 앞서, 먼저 스팀에 대한 이해가 필요합니다. 가상화폐 거래소에서 거래를 해본 경험이 있으신 분들은 스팀(STEEM)과 스팀달러(SBD)를 보신 적이 있을 것입니다. 가상화폐 거래소에서 거래되는 두 가지 화폐에 대해 쉽게 설명하면, 스팀은 비트코인과 같이 블록체인의 블록이 발행되면서 생기는 가상화폐입니다. (스팀은 비트코인과 그 가상화폐 보상을 받는 방식이 상이하지만, 이는 뒤에서 자세히 다루도록 하겠습니다.) 하지만 스팀의 경우, 여러 이슈와 시장 상황에 따라 가치의 득락이 빈번하게 이루어질 수 있기 때문에 그 가치를 보전할 수 있는 대체제가 필요합니다. 마치 전쟁 시를 대비해 금을 쟁여두고 있는 처럼요. 스팀달러(SBD)는 최소 1달러선을 보전하는 안전 자산의 개념이라고 보시면 됩니다. 암호토큰인 스팀의 가치가 유동적이기 때문에 실물 화폐와 같이 화폐가치가 비교적 안정적인 스팀달러를 개발했다고 합니다. 스팀잇은 내부에서 스팀/스팀달러 거래를 가능하게 하여 외부 거래소의 특정인에 의한 시장가격 조작을 어렵게 만들어 보다 안정적으로 시장가격을 형성할 수 있게 됩니다. 이에 대한 자세한 설명도 뒤에서 진행하도록 하겠습니다. 

### 그럼 스팀은 뭐고 스팀잇은 또 뭐야?
[스팀 공식 홈페이지](https://steem.io) 메인 페이지를 보면, 스팀에 대해 다음과 같이 설명하고 있습니다.
> Steem is a blockchain-based rewards platform for publishers to monetize content and grow community.  (Steem은 게시자가 콘텐츠로 수익을 창출하고 커뮤니티를 성장시키는 블록 체인 기반 보상 플랫폼입니다. 즉, 스팀은 블록체인 기반 보상 플랫폼 전체를 이르는 큰 개념이라고 볼 수 있습니다.)
> <br>
> <br>
> *- Steem Public Homepage*

스팀잇은 스팀이라는 블록체인 기반 보상 플랫폼을 활용하여 스팀 설계자들이 만든 첫번째 어플리케이션으로서, 커뮤니티에 돈을 지불하는 소셜 네트워크 서비스를 이릅니다. 스팀이라는 플랫폼을 다양한 서비스(예: 스팀 기반 동영상 서비스, [디튜브](https://d.tube))에 확장 적용할 수 있을테지만 그 중에 소셜 네트워크에 적용한 것이 바로 스팀잇인거죠. 

스팀잇 창업자들은 그들의 공식 홈페이지와 [백서(Whitepaper)](https://steem.io/SteemWhitePaper.pdf)를 통해 스팀과 스팀잇에 대해 다음과 같이 설명하고 있습니다.
> Steemit is a blogging platform with it's own SMT called STEEM. These tokens are distributed to content creators and curators daily as rewards, based on community voting.(Steemit은 STEEM이라는 자체 SMT를 가진 블로깅 플랫폼입니다. 이러한 토큰은 지역 사회 투표를 기반으로 콘텐츠 제작자와 큐레이터에게 보상으로 배포됩니다.)
> <br>
> <br>
> We built Steemit on Steem to show the world the future of the web. We built it to inspire new digital content business models and apps by entreprenuers and developers.(우리는 웹의 미래를 보여주기 위해 Steem 위에 Steemit을 구축하였습니다. 우리는 기업가 및 개발자에 의해 새로운 디지털 컨텐츠 비즈니스 모델 및 애플리케이션에 대한 영감을 주기 위해 스팀잇을 만들었습니다.)
> <br>
> <br>
> *- Steem Public Homepage*
> <br>
> <br>
> Steem
> <br>
> <br>
> An incentivized, blockchain-based, public content platform.
> <br>
> <br>
> *- Steem Whitepaper Cover*

여기서 잠깐, 
중간에 낯선 용어가 하나 더 눈에 들어왔습니다. 바로 SMT입니다. SMT는 Smart Media Tokens 의 앞자리를 딴 줄임말인데, 스팀은 스팀이지, SMT는 또 뭘까요? SMT는 스팀 플랫폼이 처음 등장한 지 한참 후에 완성되었으며, 공개된 지는 5개월 정도 밖에 되지 않은 용어입니다. 

[Ned - Smart Media Tokens: Why We're Doing It (VIDEO)](https://steemit.com/steem/@ned/smart-media-tokens-why-we-re-doing-it-video)

스팀잇은 작가/큐레이션이라는 독특하고 신선한 보상체계가 있는데 이 보상체계를 아무 사이트에서 가져다 쓸 수 있게 하는 것이 바로 SMT 입니다. 자체 코인 생성(이 기능도 당연히 같이 제공)을 통해서 말입니다.

스팀과 완전히 분리된 코인은 아니고 STEEM과 연계되는 코인을 생성하게 해줍니다. 자체 코인의 유통도 가능하며, STEEM/자체코인 ('자체코인1 -> STEEM -> 자체코인2' 형태 등) 연계로 인해 STEEM을 중심으로한 거대한 생태계가 만들어지게 됩니다. 

정리하자면, 스팀 플랫폼을 기반으로 한 보상서비스를 어떠한 서비스에도 확장 가능하도록 만든 장치라고 생각하시면 됩니다. SMT를 활용한 플랫폼으로는 [APPICS](http://appics.kr/APPICS)라고 하는 소셜미디어 서비스가 있습니다.(2018년 3분기 알파런칭 및 토큰 분배 예정)

[SMT Whitepaper](https://smt.steem.io/smt-whitepaper.pdf)  
[SMT를 활용한 첫번째 플랫폼, APPICS, Whitepaper](https://appics.com/downloads/Appics_Whitepaper.pdf)

시작하자마자, 낯선 개념들이 쏟아져 나왔는데요. 
더 재미있는 이야기를 드리기 전에 스팀잇 설립자들은 누구이며, 왜 이러한 서비스를 만들었는 지 살펴보겠습니다. 

## 스팀/스팀잇 설립 배경

스팀 백서의 서론 부분을 보면, 스팀잇 설립 배경이 잘 드러나 있습니다. 스팀잇은 그들의 백서 서론에서 다음과 같은 이야기를 하고 있습니다. (개인적으로 굉장히 소름이 돋았던 부분이라, 조금 길더라도 원문 전체를 옮겨 두도록 하겠습니다.)

> Collectively, user-generated content has created billions of dollars worth of value for the shareholders of social media companies, such as Reddit, Facebook, and Twitter. **[In 2014, Reddit hypothesized that its platform would be improved if everyone who contributed to reddit.com by posting stories, adding comments or voting were rewarded with a fair share in Reddit, Inc](http://www.forbes.com/sites/erikamorphy/2014/10/01/reddits-cryptocurrency-could-have-many-uses/#4e07b05332b9)** . Steem aims to support social media and online communities by returning much of its value to the people who provide valuable contributions by rewarding them with cryptocurrency, and through this process create a currency that is able to reach a broad market, including people who have yet to participate in any cryptocurrency economy.(Reddit, Facebook, Twitter 등 소셜 미디어 사용자들이 생성한 콘텐츠는 해당 기업들의 주주들에게 수십억 달러에 달하는 가치를 창출했다. 2014년, Reddit은 글 쓰기, 댓글 쓰기, 투표 등을 통해 reddit.com에 기여하는 모든 사람들에게 Reddit, Inc 주식으로 보상할 경우 자사 플랫폼이 개선될 것이라는 가설을 제기하였다. 스팀은 귀중한 기여를 하는 사람들에게 암호화폐를 보상하는 방식으로 가치의 상당량을 돌려줌으로써 소셜 미디어 및 온라인 커뮤니티를 지원하는 것을 목표로 한다. 이 과정에서 아직 암호화폐 경제에 참여하지 않고 있는 사람들을 포함한 좀더 넓은 시장까지 유통될 수 있는 화폐를 생성한다.)
> <br>
> <br>
> There are some key principles that have been used to guide the design of Steem. The most important principle is that everyone who contributes to a venture should receive pro-rata ownership, payment or debt from the venture. This principle is the same principle that is applied to all startups as they allocate shares at founding and during subsequent funding rounds.(스팀을 디자인하는데 있어서 적용된 몇 가지 핵심 원칙들이 있다. 가장 중요한 원칙은 벤처 기업의 성장에 기여한 모든 사람들이 기여도에 따라 그에 상응하는 지분, 현금 혹은 차입금을 받아야 한다는 것이다. 이 원칙은 모든 벤처 기업들의 설립 및 유상 증자 시 적용되는 주식 배분 원칙과 동일하다.)
> <br>
> <br>
> The second principle is that all forms of capital are equally valuable. This means that those who contribute their scarce time and attention toward producing and curating content for others are just as valuable as those who contribute their scarce cash. This is [the sweat equity](https://www.investopedia.com/terms/s/sweatequity.asp) principle and is a concept that prior cryptocurrencies have often had trouble providing to more than a few dozen individuals.(두번째 원칙은 모든 형태의 자본은 동등하게 가치가 있다는 것이다. 콘텐츠 생산과 큐레이션에 시간과 노력을 쏟은 이들은 자본 투자한 자들 못지 않게 가치가 있다. 이것이 땀에 대한 보상원칙이며 이전의 암호화폐들이 대다수 사람들에게 실패한 이유이기도 하다.)
> <br>
> <br> 
> The third principle is that the community produces products to serve its members. This principle is exemplified by credit unions, food co-ops, and health sharing plans, which serve the members of their community rather than sell products or services to people outside the community.(세번째 원칙은 커뮤니티는 그 소속 멤버들을 위한 제품을 만들어야 한다는 점이다. 이 원칙은 신용협동조합, 식품협동조합, 의료비공동부담플랜 등에서 검증된 바 있는데, 이런 협동조합은 커뮤니티 외부의 사람들을 위해 제품이나 서비스를 제공하는 것 보다는 내부 멤버들에게 우선 서비스한다.)
> <br>
> <br>
> The Steem community provides the following services to its members: (스팀 커뮤니티는 구성원들에게 아래와 같은 서비스들을 제공한다. *(이건 조합원으로서의 우리의 의무이기도 하다.)*)
> <br>
>> 1 A source of curated news and commentary.(큐레이팅한 뉴스와 해설 등의 제공) <br>
>> 2 A means to get high quality answers to personalized questions.(개인이 필요로 하는 질문에 대한 수준 높은 답변 등 제공) <br>
>> 3 A stable cryptocurrency pegged to the U.S. dollar.(US 달러에 연동하는 안정적인 암호화폐) <br>
>> 4 Free payments.(거래 수수료 면제) <br>
>> 5 Jobs providing above services to other members.(다른 멤버들에게 위의 서비스를 제공하는 일을 제공) <br>

> Steem’s purposeful realignment of economic incentives has the potential to produce fairer and more inclusive results for everyone involved than the social media and cryptocurrency platforms that have gone before it.(스팀이 지향하는 경제적 인센티브의 재조정은 이전의 소셜 미디어 및 암호화폐 플랫폼들보다 좀 더 공정하고 포괄적인 결과를 만들어낼 것으로 기대된다.) 
> <br>
> <br>
> *- Steem Whitepaper Introduction*

백서의 내용을 토대로 보면, 결국 스팀은 그 동안 페이스북, 트위터, 레딧 등과 같은 소셜미디어의 주주 및 투자자들이 그 플랫폼 사용자들이 생성한 콘텐츠를 기반으로 거대한 부를 축적해오던 것에 대해 반감을 가지고 있던 네트 스캇(Ned Scott, CEO)과 댄 라리머(Dan Larimer, CTO, 현 EOS 창립자) 두 사람은 2014년 레딧이 자신의 플랫폼인 Reddit.com에 글을 포스팅 하거나, 댓글을 달거나, 보팅(좋아요)을 하는 기여자들에게 레딧 회사의 주식을 줄 경우 플랫폼이 좀 더 발전할 것이라는 가설을 제기하자 이를 실현하는 시도를 하기 위해 **소셜미디어(커뮤니티)에 실질적으로 기여한 모든 사람들에게 보상이 돌아가는 새로운 미디어 회사 스팀잇을 2016년 1월에 설립하게 된 것**입니다. 

기존 소셜미디어들은 커뮤니티 멤버들이 작성한 콘텐츠를 등에 업은 거대 트래픽을 기반으로 하며, 그 트래픽에서 발생하는 광고수익, 회사 가치 상승에 따른 혜택이 커뮤니티 멤버들 보다는 자본을 투자한 일부 주주들에게 대부분 돌아갑니다. 즉, 주주 자본주의(Shareholder Capitalism)를 기반으로 하며 리스크를 많이 지고 투자를 빨리한 순서 대로 부(Wealth)를 더 가져가게되는 것이죠. 창업자가 제일 많은 부를, 그 다음엔 초기 엔젤투자자, Series A 투자자, 성장단계 투자자, 공모(IPO) 투자자 순입니다. 정작 그 커뮤니티를 키운 건 우리 같은 일반 이용자들인테 말입니다.

> Steem is designed from the ground up to address the major barriers to adoption and monetization of a social media based economy.(스팀은 소셜미디어 기반 경제 시스템이 받아들여지고 수익화하는데 가로막는 장벽들을 해소하기 위해 처음부터 디자인되었다.)

### 스팀에서 말하는 기여 가치 

> The value of most content is so low relative to the cognitive, financial, and opportunity costs associated with making a payment that few readers choose to tip. The abundance of free alternatives means that enforcing a ‘paywall’ will drive readers elsewhere.(대부분의 콘텐츠의 가치는 인지적 비용, 금전적 비용, 기회 비용에 비해 상대적으로 매우 낮아서 거의 독자들이 지불하지 않으려 한다. 무수히 많은 무료 대체 콘텐츠들이란 ‘지불 장벽’이 독자들을 다른 곳으로 내몬다.)

스팀은 콘텐츠의 가치를 인지적 비용, 금전적 비용, 기회 비용의 3가지 관점에서 접근합니다. 

> Cognitive Cost(인지적 비용): IGI Global에선 ‘Costs deriving from divergent mindsets. Those may be costs due to conflicts which have their origin in incompatible worldviews or costs induced by learning in an effort to bring differing mental patterns and knowledge closer.’ 라고 정의하고 있습니다.

통상 우리는 지식 콘텐츠를 인지하고 머리를 굴리고 읽을까 말까 고민하고 검색하고 여기서 잘못된(허접한) 콘텐츠를 만나면 어떻게 하지 고민도 하면서 정신적인 갈등도 겪고 합니다. 이게 다 엄청난 비용인 것입니다. 지식에 가깝게 가기 위한 비용. 그것도 엄청나게 내적갈등을 유발하는 비용이 드는 것이죠. 이렇게 쏟아부은 비용 대비 온라인 콘텐츠의 가치(가격)는 상대적으로 낮다는 의미입니다. 좋은 온라인 콘텐츠는 충분한 가치를 인정받아야 됨에도 불구하고 말입니다.

> Financial Cost(금전적 비용)  

금전적 비용에 대해서는 별도의 설명이 없어도 이해가 되겠지요?

> Opportunity Cost(기회 비용) 위키피디아에 의하면 기회비용은 ‘ 하나의 재화를 선택했을 때, 그로 인해 포기한 것들 중 가장 큰 것의 가치’를 말한다. 

여자친구와 영화 보는게 가장 가치가 큰 걸 앎에도 불구 스팀잇에서 블록체인 글을 읽기로 했는데 그 글이 형편없다면 전 엄청난 기회비용을 들인 것일 것입니다. 그 기회비용 대비 온라인 콘텐츠의 가치(가격)는 상대적으로 매우 낮은 현실입니다.

> Steem is designed to enable effective micropayments for all kinds of contribution by changing the economic equation. Readers no longer have to decide whether or not they want to pay someone from their own pocket, instead they can vote content up or down and Steem will use their votes to determine individual rewards. This means that people are given a familiar and widely used interface and no longer face the cognitive, financial, and opportunity costs associated traditional micropayment and tipping platforms.(스팀은 경제학적 방정식을 변경함으로써 모든 종류의 기여에 효과적으로 소액지급 될 수 있게 설계되었다. 독자들은 더이상 자신의 지갑에서 누구에게 지불해야 할지 혹은 안해야 할지 결정하지 않아도 된다. 그 대신 손 쉽게 Up 또는 Down 으로 투표하면 스팀이 그런 투표결과를 가지고 각자의 보상을 결정할 것이다. 사람들은 아주 친숙한 UI 환경상에서 더이상 플랫폼을 후원하고 전통적인 소액지급(결제)와 관련된 인지적 비용, 금전적 비용, 기회비용 문제를 직면하지 않을 것이다.)
> <br>
> <br>
> Voting input from community members is critical for Steem to accurately allocate payments to contributors. Voting can therefore be viewed as a crucial contribution and worthy of rewards on its own. Some platforms, such as Slashdot, use meta-moderation as a way to rank and reward honest moderators. Steem chooses to reward those who contribute the most to the total promotion of a piece of content and rewards the voters proportional to the ultimate reward paid to the content creator.(커뮤니티 멤버들의 보팅은 각 기여자들에게 정확히 보상을 배분하는데 매우 중요하다. 그렇기에 보팅은 매우 중요한 기여로 볼 수 있고, 보상할 가치가 있다. 슬래쉬닷 같은 플랫폼은 메타중재라는 방식으로 정직한 중재자들을 평가하고 보상을 정한다. 스팀은 콘텐츠 흥행에 가장 많은 기여를 한 사람을 선택해 보상하고 콘텐츠 제공자에게 주어진 전체 보상에 비례하여 투표자들에게도 보상한다.)

위의 내용에서 보면, 메타중재라는 표현이 등장합니다. 스팀도 마찬가지로 이러한 메타중재 방식을 도입하여 21명의 증인이라는 것을 투표로 선정하도록 합니다. 이 21명의 증인의 역할과 의미에 대해서는 뒤에서 더 자세히 다루도록 하겠습니다. 

### 스팀의 세 가지 원칙

스팀의 vision을 실현시키기 위한 그들이 제시한 세 가지 원칙에 대해 다시 살펴보면 다음과 같습니다. 

> 제 1원칙 : 자금조달(Financing)에 대한 보상/책임

자본 조달에 참여한 모든 이들은 그에 따른 보상을 받아야 한다는 것입니다. 자본 조달은 주식을 발행하여 자본화 시키거나(Ownership), 지분제공 없이 차입하여 부채로(Payment or Debt) 조달이 가능한데 이 두 조달방식 모두에게 보상은 돌아가야 한다는 게 **제 1원칙 : 자금조달(Financing)에 대한 보상/책임** 에 대한 내용입니다. 

> 제 2원칙 : 땀에 대한 보상(Sweat Equity)

스팀잇 서비스 안에서 땀에 대한 보상은 스팀달러(STEEM DOLLARS, SBD)와 스팀파워(STEEM POWER, SP)로 이루어집니다. 그리고, 스팀달러는 스팀으로 전환되어 자본화 되기도 합니다. 즉, 노동지분이 자본지분으로 바뀌는 것이죠.

> 제 3원칙 : 신용협동조합(Credit Union)

커뮤니티에 속한 조합원 개념입니다. 스스로 주인이면서 생산의 주체가 되고 소비의 주체가 되는 것이지요. 

그럼 신용협동조합의 원칙이 스팀 커뮤니티에는 어떻게 적용되었을까요?

‘저’로 비유를 들면, 저는 스팀잇에 가입한 순간부터 스팀잇 이라는 협동조합의 멤버가 되었습니다. 그렇기에 저는 커뮤니티를 위해 글을 쓰고 코멘트를 달고 리스팀을 해야 한다(노동력 제공). 열심히 글을 쓰면 저에게도 보상이 돌아옵니다. 그 보상은 스팀달러와 스팀파워 형태로 오는데 스팀달러는 스팀으로 전환가능한 채권(Note) 형태라 전 커뮤니티로부터 받을 채권이 있는 셈이다(동시에 커뮤니티 일원으로 채권을 부담할 책임도 지겠지요). 물론 일정 시간이 지나면 스팀으로 전환하여 주주로 바뀔 수도 있습니다.

저는 콘텐츠 생산자이면서 동시에 소비자이기도 합니다. 그렇기에 소비자(독자)로서 업보트(upvote, 추천, 투표)도 해야 한다. 업보트를 하기 위해서는 스팀파워가 필요합니다. 스팀파워는 초기에 없기 때문에 먼저 들어온 조합원에게 빌려(임대하여)서 쓸 수 밖에 없습니다. 아니면 스팀을 시장에서 사서(투자, Ownership) 그것을 파워업하여(Powering Up)하여 스팀파워로 바꿔 업보트에 참여해야 합니다.

이 과정에서 어뷰징을 하게 되면 커뮤니티 전체가 다치게 됩니다. 그건 주주이며, 채권자이며, 조합원인 저로서는 해서는 안되는 행동입니다. 즉, 커뮤니티의 구성원(이용자) 스스로도 자정노력을 하게 되는 것이죠.

뭔가 자본주의와 사회주의 전반을 오가며, 기존의 경제학적 관점에서 정형화된 틀을 비꼬고 있습니다. 스팀 백서의 초반부는 정말 잘 쓰여진 선언문과 같은 느낌입니다. 시대에 대한 도전장으로 보이기도 포부로 보이기도 출사표로 보이기도 합니다. 

그럼 이번에는 도대체 이런 생각을 하고 실행까지 시키고 그 실행을 성공까지 시키고 있는 놈들(?)은 대체 어떤 놈들(?)일 지 알아보겠습니다.

[*- 참고글 : @mechuriya*](https://steemit.com/@mechuriya)

### 스팀잇 창업자

스팀잇은 앞서 설명한 것 처럼,  **네드 스캇(Ned Scott)** 스팀잇 공동창업자 겸 최고경영자(CEO), **댄 라리머(Dan Larimer)** 스팀잇 공동창업자 겸 최고기술책임자(CTO)가 2016년 1월 설립했습니다. 

포브스가 "세상에서 가장 빠르고 가장 빠르게 성장하는 블록체인 응용 프로그램 중 하나"라고 평가한 스팀잇의 시발점은 2015년 중순으로 거슬러 올라갑니다. 네드 스캇과 댄 라리머가 전화통화를 처음 한 것이 이 무렵입니다. 온라인 채팅으로 대화하던 두 사람은 전화로 대화를 나누면서 블록체인을 기반으로 한 새로운 애플리케이션을 만들기로 뜻을 모으게 됩니다. 

컴퓨터 과학자 댄 라리머를 먼저 알아본 것은 재무 전문가 네드 스캇입니다. 네드 스캇은 베이츠 대학교(Bates College)에서 심리학과 경제학을 전공했습니다. 이후 100년 이상의 역사를 지닌 북미 지역 식품 수입 업체 겔러트 글로벌 그룹(Gellert Global Group)에서 3년 동안(2012~2015년) 사업 운영 및 재무분석가로 일했죠. 그는 2013년 야후에서 경제 뉴스를 읽다 비트코인이라는 개념을 처음 접했는데요. 네드 스캇은 가상화폐로 작동하는 경제에 매료됐고, 비트코인에 대해 공부하기 시작했습니다. 그러던 중 네드 스캇은 컴퓨터 과학자 댄 라리머에 대해 알게 됩니다. 

미국 콜로라도에서 태어난 댄 라리머는 2003년 버지니아폴리테크닉 주립대학교에서 컴퓨터 과학 학사 학위를 취득했습니다. 댄 라리머는 2009년부터 가상화폐에 대한 연구를 시작해 블록체인 플랫폼 비트쉐어(Bitshares)을 만들었습니다. 또한, 댄은 그의 아버지 스탠 라리머(Stan Larimer)와 세운 블록체인 기술 컨설팅 회사 크립토노멕스(Crytonomex)의 CEO를 맡고 있는 블록체인과 가상화폐 전문가입니다. 

네드 스캇은 2016년 5월 코인리포트와의 인터뷰에서 "내가 비트코인을 알게 된 지 8개월 뒤인 2년 반 전에 댄을 알게 됐다"며 "비트쉐어 프로젝트에서 댄의 작업을 보면서 비트코인 토끼 구멍에서 빠져나온 기분이 들었다"고 말했습니다. 

네드 스캇은 2015년 중반 첫 통화를 한 뒤, 2016년 초 댄 라리머를 만나러 갔습니다. 두 사람은 2016년 1월 블록체인을 이용한 서비스에 대한 아이디어를 모았고, 그해 3월 스팀잇 메인 홈페이지를 만들어 2016년 4월 알파 테스트를 진행했습니다. 

애초 네드 스캇과 댄 라리머가 구상한 모델은 블록체인 기반의 보험 네트워크 서비스였습니다. 하지만 두 사람은 과연 사람들이 자신들이 만든 보험 서비스에 돈을 투자할 지 의문이 들었습니다. 그래서 이들은 참여자들에게 책임을 물을 수 있는 방법을 고안했습니다. 사용자가 토론에 참여할 수 있는 강력한 커뮤니케이션 포럼을 만들어 참여자가 서로의 콘텐츠를 평가할 수 있도록 한 것입니다. 

네드 스캇은 2016년 5월 코인리포트와의 인터뷰에서 "우리는 블록체인을 기반으로 한 마이크로 보험과 같은 몇몇 아이디어를 굴렸지만, 궁극적으로 가상화폐를 가장 유용하게 활용할 수 있는 모델은 커뮤니티라고 생각했다"라며 "사람들이 피어 투 피어 (peer-to-peer) 방식으로 서로를 돕고 문제를 해결할 수 있는 서비스를 만들자는 아이디어가 결국 스팀잇을 만들었다"고 말했습니다. 

이에 앞서 댄 라리머은 네드 스캇을 만난 이후인 2015년 12월 개인 블로그에 올린 '공제조합(Mutual Aid Society)'이라는 글을 통해 '믹서(MUXER)'라는 '상호 도움이 되는 사회적 네트워크' 개념을 언급했습니다. 

네드 스캇은 "댄 라리머와 스팀잇 개발자의 경력을 합하면 블록체인 기술을 다룬 것만 12년 이상이다"라며 "그 덕분에 빠른 시간 안에 스팀잇을 선보일 수 있었다"고 말했습니다. 

얼핏 보기에 여타 소셜미디어 서비스와 차이가 없어 보이는 스팀잇의 특징은 블록체인을 기반으로 한 투명성에 있습니다. 스티머가 스팀잇에서 글을 쓰는 등의 모든 작업은 블록체인에 기록됩니다다. 즉, 올린 글이나 업보트 기록, 사용자별 보유하고 있는 스팀 금액조차 공개됩니다다. 그 때문에 스팀잇에 올린 콘텐츠는 7일이 지나면 수정이나 삭제를 할 수 없습니다. 

네드 스캇은 IT 전문 매체 와이어드에 "레딧처럼 집단의 인정을 기반으로 움직여 비슷한 서비스로 보이지만, 전혀 다르다"며 "스팀잇에서는 스팀을 벌 수 있다"고 강조했습니다. 

네드 스캇은 2016년 5월 코인텔레그라프에 "스팀잇은 게시자에게 접근 권한을 부여하고 제3자의 광고 없이 콘텐츠로 수익을 창출할 수 있도록 했다"며 "우리의 주된 목표는 좋은 사람을 플랫폼으로 끌어들여 점점 더 긍정적인 온라인 커뮤니티를 구축하는 것이다"라고 말했습니다. 

네드 스캇은 이어 "가상화폐를 처음 접했던 2013년 월스트리트에서 한평생을 보낸 아버지에게 가상화폐를 어떻게 생각하는지 물었더니 '아들아, 나는 유행에 이끌려다니지 않으려고 노력한다'라고 말했다"며 "나에게 가상화폐는 더 이상 유행이 아니며 수십억명의 삶을 바꿀 잠재력이 있는 어떤 것이다"라고 말했습니다. 

스팀잇 직원은 2017년 1월 15명에서 그해 10월 30명으로 늘 정도로 성장세가 무섭습니다. 네드 스캇은 미국 텍사스주 오스틴에 위치한 본사에서 플랫폼 및 소프트웨어 개발을 지원합니다. 다만, **댄 라리머는 2017년 3월 최고기술책임자(CTO) 자리에서 물러났으며** 스팀잇에는 계속 게시물을 올리고 있습니다. 두 사람은 "분쟁없이 우호적인 조건에 이르렀다"며 각자의 길을 갈 것임을 선언했습니다. 

댄 라리머는 현재는 이오스(EOS) 블록체인 플랫폼을 만드는 블록원의 CTO를 맡고 있습니다. 그는 최초로 '탈중앙화된 자율 회사' (Decentralized Autonomous Company, DAC)를 고안했습니다.

[*- 참고기사*](http://it.chosun.com/news/article.html?no=2846901)  
[*- 스팀센터 위키 : 댄라리머*](https://www.steem.center/index.php?title=%EB%8C%84_%EB%9D%BC%EB%A6%AC%EB%A8%B8)  
[*- 오스트리아 학파 : 댄라리머*](https://steemit.com/kr/@creamer7/3113vm)  
[*- 스팀잇의 위기? 이오스 기반의 새로운 탈중앙화 SNS는 나올 것인가? 네드의 다운보팅 사건*](https://steemkr.com/kr/@solucher/sns)  
[*- 비탈릭 부테린과 댄 라리머의 이더리움 vs. EOS 논쟁 해설*](http://www.hashedpost.com/2017/08/hashed-report-vs-eos.html)  

## 스팀의 가상 경제 시스템
이제 본격적으로 (아직도 본격이 아니었다니!) 스팀잇의 실제 운영 구조에 대해 이해해 보도록 하겠습니다.   
스팀잇을 이해하는데, 가장 중요한 것은 바로 **스팀-스팀달러-스팀파워**의 3자 구조로 이루어진 가상 경제 시스템을 이해하는 것입니다.

스팀은 앞서 설명한 것 처럼 커뮤니티에 기여하는 모든 사람이 그 기여에 대한 적절한 보상을 받아야함을 전제로 하고 있습니다.

커뮤니티에 기여한다는 것의 의미는 해당 커뮤니티의 자본 출자에 어떠한 기여를 했는가로 해석할 수 있습니다. 자금 출자에는 두 가지 방식이 있는데, 스팀 백서는 이 두 가지가 다 스팀 커뮤니티 성장을 위해 중요하다고 말하고 있습니다. 그러면서 다음과 같이 추가로 설명합니다. 

> Both types of capital contributions are valuable to the growth of the community and value of its currency. Additionally there are two ways ownership can be held: liquid and vesting. Vesting ownership makes a long-term commitment and cannot be sold for a minimum period of time. (자금 조달의 두가지 방식 모두 커뮤니티의 성장과 화폐가치 유지에 매우 중요하다. 자본출자는 두가지 방식이 있는데 그게 시장매수와 권리부여 방식이다. 권리부여 방식은 장기적인 약속이며 특정한 기간 동안 매각할 수 없음을 의미한다.)

지분에 의한 자금조달은 스팀 커뮤니티 입장에선 비교적 안정적인 자금조달 방식입니다. 당장 상환해야될 것도 아니고, 투자자 입장에선 비록 리스크가 있지만 커뮤니티(또는 회사)의 성장에 따른 자본이득(Capital Gain, 여기에선 스팀 가격 상승에 따른 투자이익), 사업 실패에 따른 자본손실(코인 투자손실)을 모두 포함하고 있습니다. 반면, 부채로 조달할 경우에는 지분의 희석(Dilution) 없이 원금과 이자만 상환하면 되기 때문에 시장에 풀린 주식수가 추가 늘어나지 않게 됨으로서 주가에 긍정적인 영향을 미친다.(이 부분이 요즘 이야기 나오는 리버스 ICO가 주주의 이익과 충돌이 난다는 것과 이어지는 이야기입니다.)

지분(주식)으로 생각하니 좀 어렵게 느껴지겠으나 이걸 시장에 풀린 돈이라 생각하면 좀 더 이해가 쉽습니다. 돈이 무분별하게 많이 풀리면 돈가치가 떨어지는, 즉 인플레이션 현상이 나타날 수 밖에 없습니다. 스팀만 발행하여 시장에서 자금을 조달하게 되면, 부채로 조달하는 것에 비해 상대적으로 암호화폐 시장에 스팀이 너무 많이 풀릴 수 있습니다. 그래서, 그 가격을 안정시킬 방법이 필요합니다. 이를 해결하는 방식으로 **돈을 조달하되 시장에 풀지 않는 부채방식을 고안**한 것입니다. **이렇게 해서 나온 것이 스팀달러(SBD)** 이다. 스팀달러는 우리가 글을 쓸 때 스팀 커뮤니티가 저자에게 주는 보상 중 하나입니다. 스팀 입장에선 저자에게 지는 부채인데 이걸 바로 주식화(스팀)하여 시장에 풀어 팔아버리면 스팀가격 유지가 쉽지 않을 수 있습니다. 원칙상으로는 저자에게 바로 스팀을 줘야 하는데 그럼 스팀이 시장에 즉시 풀리게 되고 그걸 바로 팔아버리면 스팀가격 유지도 어려워 질 수 있고, 결론적으로 스팀 에코시스템에 영향을 줄 수 있습니다. 

앞서 본 바와 같이, 스팀은 그들의 백서에서 자본출자의 두가지 방식, Liquid(시장 매수) 와 Vesting(권리 부여)에 대해 이야기하고 있습니다. 

'Liquid'는 또 두가지로 나눌 수 있는데 스팀이 처음 ICO할 때 참가하여 스팀 커뮤니티에 유동성을 공급하는 방식(물론, 그때 조달한 돈으로 스팀잇을 개발해오는 거지만)과 ICO 이후 우리 같은 개미들이 시장에 상장된 스팀을 사는 방식입니다. 그런데 후자의 방식은 스팀가격 유지에는 도움이 될 수 있으나 스팀 커뮤니티에 추가 자금적 도움은 주지 못합니다. 그렇기에 시장에 있는 유동성 풍부한 스팀중 일부를 스팀 커뮤니티 내부로 끌여들여 유동성을 제한하는 자본 형태로 바꾸거나(Power Up) 아니면 채굴(글 쓰기, 리스팀, 블록체인 유지, 증인자의 역할 수행 등)에 기여한 자들에게 유동성이 제한된 화폐(스팀 파워)를 공급하거나 하는 방식을 취하게 된 것입니다. 이 방식을 스팀 백서에선 'Vesting'으로 표현한 것입니다.

### 스팀(STEEM)
> Steem is the fundamental unit of account on the Steem blockchain. All other token derive their value from the value of STEEM. STEEM is a liquid currency, and therefore can be bought or sold on exchanges, as well as to other users as a form of payment.(스팀은 스팀 블록체인 상의 기본 계정단위이다. 모든 다른 토큰(스팀 파워, 스팀 달러)들의 가치는 스팀 가치를 기본으로 산정된다. 스팀은 유동성 있는 화폐로 거래소에서 사거나 팔 수 있고 지불의 수단으로 사용될 수 있다)

스팀은 스팀 블록체인 상의 기본 화폐입니다. 그리고, 가상세계와 현실세계를 연결하는 매개체입니다. 스팀 커뮤니티 상에서 통용되는 화폐(스팀파워, 스팀달러)는 스팀을 통해 원화, 달러 등 현실상의 'Fiat Money'로 바꿀 수 있단 얘기입니다. 

스팀은 자본출자 방식 중 첫 번째인 'Liquid'에 해당다. 그리고, 다음은 자본출자 방식 두번째인 'Vesting'에 대해 설명해보겠습니다. 바로 스팀파워입니다.

### 스팀파워(Steem Power, SP)
> Start up companies require long-term capital commitment. Those who invest their money in a startup expect to wait years before they can sell their shares and realize their profits. Without long-term commitment, a startup seeking to raise additional capital through the sale of additional shares would be competing with existing shareholders looking to exit. Savvy investors want their capital contributions to grow the company, but growth cannot happen if the new capital is given away to those looking to exit. There is significant value to having long-term commitment because it enables communities to make long-term plans. Long term commitment of stakeholders also causes them to vote for long-term growth rather than short-term pumps. In the cryptocurrency space, speculators jump from cryptocurrency to cryptocurrency based mostly on which one is expected to have short-term growth. Steem wants to build a community that is mostly owned and entirely controlled by those with a long-term perspective.

스타트업은 장기 투자자를 필요로 합니다. 그래서 초기에는 차입 보다는 자본을 통한 조달을 선호하지요. 스타트업에 투자하여 지분(주식)을 취득하게 되면 그 회사의 주주가 되고 그 회사 장기성장을 위해 투자자도 노력을 합니다. 돈을 빌려주는 채권자는 회사의 장기성장 보다는 상대적으로 회사가 망하지 않는 것을 위해 노력합니다. 이게 일반 주식회사 구조에서 자금조달의 일반적인 모습입니다.

그런데 토큰 이코노미는 다릅니다. 스팀 커뮤니티가 코인을 발행할 때 ICO에 참가하여 그 코인을 사면 우린 코인 투자자가 됩니다. 초기에 ICO로 들어온 자금은 스팀 커뮤니티 성장에 도움을 줍니다. 그런데 ICO로 (저가에) 스팀을 확보한 투자자가 거래소에서 스팀을 팔아버리고 그 판 스팀을 산 고객들은 회사의 장기적인 발전 보다는 시장에서의 스팀 가격에만 관심을 가지게 됩니다. 회사 장기성장에 도움이 안되는 투자자란 얘기입니다. 이 부분이 스타트업의 구조와 다릅니다. 스타트업 초기 투자자는 회사의 장기 성장을 위해 노력을 하는데 시장에서 코인 구매자는 그 커뮤니티 성장에 (스타트업을 위한) 스타트업 투자자 만큼의 관심이 덜하게 됩니다. 또한, 스타트업 초기 투자자는 IPO 전까지 그 지분을 팔기 힘듭니다. 시장도 없을 뿐더러 사는 이들도 없습니다. 

토큰 이코노미에선 이 문제를 해결해야만 합니다. ICO 이후의 지속적인 자금유입 문제, 코인 구매자들의 지속적인(장기적인) 커뮤니티 참여(기여) 유도, 코인 가격 유지 등의 문제를 해결해야 합니다. 그리고 스팀은 장기적인 관점으로 코인을 보유하고 그런 사람들에 의해 지배되는 커뮤니티를 만들고 싶어 합니다. 

어떻게? 여기서 'Vesting' 구조가 이용됩니다. 'Vesting'은 통상적으로 근무기간이나 성과에 따라 연도별로 주식을 부여하는 방식입니다. 스탁옵션과 약간 다릅니다. 스탁옵션이 일정 가격에 주식을 살 수 있는 권리를 갖는 개념이라면(권리 행사 안해도 됨) 'Vesting'은 회사가 주식을 부여하는(회사가 일정 기간 지나면 주식을 줌) 개념입니다.

#### 스팀파워를 구입하는 방법

스팀파워는 두가지 방식으로 구입할 수 있습니다. 첫번째가 'Liquid' 방식(자본에 의한 조달)으로 시장에서 스팀을 구매하여 그것을 파워업(Power Up)하여 스탐파워로 바꾸는 방식입니다. 이렇게 할 경우 시장에서 스팀 구매자(스팀 커뮤니티에 자금 유입도 안시킨 그냥 코인 구매자)의 스팀을 장기투자로 변환시킬 수 있고, 시장의 유동성을 축소시켜 인플레이션도 방지하기 때문에 코인가격 유지에도 좋고 건강한 스팀 에코시스템의 유지에도 도움이 됩니다. 

두번째 방식이 노동(Sweat)에 의한 조달 방식입니다. 즉, 스팀 커뮤니티에 노동력(작가, 큐레이팅, 댓글, 블록체인 제공 등)을 제공한 대가로 스팀파워를 받는 방식입니다. 물론 스팀파워를 주는 사람들도 같은 커뮤니티 멤버입니다. 그들은 업보트를 통해 스팀파워를 줄 수 있습니다. 우리가 돈도 내고 생산도 하고 돈도 받는 것입니다. 이건 완전한 신용협동조합(Credit Union) 구조입니다. 

스타트업에서는 지분으로 자금을 조달하면 그 자체가 장기투자가 됩니다. 토큰 이코노미는 다릅니다. 스팀이 스팀파워 구조를 설계했다고 하더라도 장기투자 구조를 만들어야 합니다. 거기에 쓰인 개념이 'Vesting' 입니다.  

#### 스팀파워의 'Vesting' 구조

스팀잇은 스팀으로 파워업하는 경우 스팀파워로 변환해 줍니다. 스팀파워는 실체가 애매한(?) 화폐이다. 자본도 아니고 부채도 아니고. 스팀파워 보유자는 13주 동안 매각이 제한되는 화폐를 구매한 셈이 됩니다.(스팀파워는 즉시 스팀으로 교환이 되지 않고 13주에 걸쳐 13분의 1씩 교환됩니다.) 시장에서 자유롭게 유동화가 불가능한 화폐를 산 것에 대한 대가를 스팀 커뮤니티는 제공해야 합니다. 스팀 커뮤니티는 Power(영향력)와 이자를 제공합니다. 

'One-User, One-Vote'로 운영되는 대부분의 소셜미디어와 달리 스팀 커뮤니티는 'One-SP, One-Vote'로 운영됩니다. 즉, 유동성을 포기하고 어려운 선택을 한 스팀파워 보유자에게 투표영향력을 보상하는 것입니다. 노동력(Sweat)에 의해서도 스팀파워를 획득할 수 있으므로 결론적으로 스팀파워의 영향력은 '자본+노동력'의 산물이며, 그게 단순히 쪽 수(One-User, One-Vote) 보단 커뮤니티 영향력 행사 수단으로 더 낫다고 본 것입니다.

유동성 포기의 대가로(시세차익을 맛볼 기회를 상실한 것에 대한 보상) 스팀 커뮤니티는 15%의 이자도 지불합니다. 유동성을 다시 되찾기 위해서는 스팀으로 파워다운(Power Down) 해야하고 스팀파워는 13주간에 걸쳐 균등하게 스팀으로 권리회복 됩니다. 

즉, 스팀파워 보유자는 13주 동안의 파워 다운(Power Down) 과정을 거쳐야 스팀을 보유하게 되는 것이고 스팀은 이런 시스템을 기존 스타트업의 'Vesting(권리부여)' 구조에서 차용해온 것입니다. 


### 스팀달러(Steem Dollars, SBD) 
스팀파워가 유통주식의 고정화 개념이라면, 스팀달러는 부채로 인한 자금조달이면서 시장 안정화 기능을 합니다.
> Stability is an important feature of successful global economies. Without stability, individuals across the world could not have low cognitive costs while engaging in commerce and savings. Because stability is an important feature of successful economies, Steem Dollars were designed as an attempt to bring stability to the world of cryptocurrency and to the individuals who use the Steem network.(안정성은 성공적인 글로벌 경제에서 중요한 요소이다. 안정성 없이는 상거래와 저축에 참여하는 사람들의 인지비용을 낮춰줄 수 없다. 그 이유는 안정성은 글로벌 경제 성공의 중요한 요소니깐. 스팀달러는 암호화폐 세계와 스팀 네트워크를 사용하는 사람들에게 안정성을 제공하기 위해 설계되었다.)
> <br>
> <br>
> Steem Dollars are created by a mechanism similar to convertible notes, which are often used to fund startups. In the startup world, convertible notes are short-term debt instruments that can be converted to ownership at a rate determined in the future, typically during a future funding round. A blockchain based token can be viewed as ownership in the community whereas a convertible note can be viewed as a debt denominated in any other commodity or currency. The terms of the convertible note allow the holder to convert to the backing token with a minimum notice at the fair market price of the token. Creating token-convertible-dollars enables blockchains to grow their network effect while maximizing the return for token holders.(스팀달러는 컨버터블 노트와 유사한 구조로 설계되었는데, 이 컨버터블 노트는 스타트업 투자시 자주 사용되어왔던 개념이다. 스타트업 세계에서 컨버터블 노트는 단기 차입금 같은 건데 후속 펀딩 라운드에서 미리 약속된 지분으로 변환될 수 있는 금융상품이다. 컨버터블 노트가 상품 혹은 화폐에서 부채로 간주되지만, 블록체인 기반 토큰은 커뮤니티의 지분으로 간주된다. 컨버터블 노트의 조건들은 그 보유자들이 손쉽게 토큰의 공정시장가액으로 다른 형태의 토큰으로 전환가능함을 의미한다. '현금전환토큰'은 토큰 보유자들의 수익을 극대화하면서 블록체인의 네트워크 효과를 성장시키는 역할을 한다고 생각한다.) 

'Convertible Note'는 실리콘밸리에서 초기단계 투자시 많이 쓰이는 유가증권의 종류 중 하나입니다.  'Convertible Note'는 '전환이 가능한 수표'다. 스타트업이 막 생겼는데 팀 멤버들은 똑똑한데 그 회사의 가치를 정하기도 애매하고, 그런데 투자는 빨리 하고 싶고 그걸 가능하게 해주는 상품이 없을까 해서 고안된 유가증권의 한 형태입니다.

저를 엔젤투자자라고 생각해보겠습니다. 나홀로 Bar에서 술 한잔 하는데 내 명성을 듣고 어느 창업자가 다가왔습니다. 간단히 사업 피칭을 하는데 이 놈이 괜찮아 당장 투자하고 싶은데 이 친구가 회사 Value를 100억이라 부르는겁니다. 'What the Fuck!' 이라고 하고 싶지만 참으며, 난 '자네 사업 시작한 지 얼마 되지도 않았고 그 밸류가 정확한지 모르지만 일단 내가 수표(Note) 한장 끊어 줄테니 그거 가지고 초기 사업자금으로 써라. 이자는 안줘도 돼! 내가 이자 때문에 투자하는 게 아니니깐. 그렇지만 나중에 벤처캐피탈이 투자 들어온다면 그 때 벤처캐피탈이 정한 밸류의 20% 할인된(Discounted) Value로 나에게 지분(주식)을 주면 돼'. 이게 'Convertible Note'입니다. 당연히 부채로 조달하는 것이기 때문에 상환의무가 있습니다. 그리고 후속투자가 안들어 오면 계속 'Convertible Note'상태로 남아 있거나 일정 기한 지나면 상환해야 합니다. (최근엔 상환의무가 있다는 것 조차도 짜증내는 창업자가 많아 실리콘밸리에선 SAFE(Simple Agreement for Future Equity) 형태로 간단한 계약서에 미래 투자밸류의 Discount 율(지분으로 전환되는)을 명시하여 돈을 조달하는 형식이 많이 쓰인다고 합니다. 이건 상환의무가 전혀 없어, 후속투자 못 받으면 그냥 SAFE 찢어 버리면 됩니다.)

스팀달러는 스팀 커뮤니티에서 열심히 글쓰고 댓글달고 등 노동력을 제공하면 보상으로 주어집니다. 통상 글을 쓰면 스팀달러 50%, 스팀파워 50%로 보상이 됩니다. 내가 글 쓴 것에 대한 노동력의 대가이니 스팀 커뮤니티는 나에게 돈을 줘야 합니다. 그런데 내 원고료(저자보상금액)가 급등락하는 스팀가격에 연동이 되어 있음 난 글을 지속적으로 스팀잇에 쓸 수 없습니다. 그러니 내가 받을 채권(저자보상)은 현실세계 화폐로 고정(안정화)을 해주는 것, 그게 스팀달러입니다. 스팀달러는 원래 받아야할 달러금액에 맞춰 스팀으로 전환비율이 조정되며, 이 돈은 교환을 원할 경우, 3.5일 후 스팀으로 변환됩니다. 스팀달러는 미국 달러와 1:1 연동되어 실제 저자 보상금액이 급변하는 것을 막아줍니다. 

### 증인(Witness)

가상화폐 시스템은 채굴이라는 독특한 방식으로 화폐를 찍어냅니다. 비트코인은 새로운 블록을 생성할 때 컴퓨터 파워를 제공하는 사람(채굴자)에게 가상화폐를 제공합니다. 컴퓨터 리소스를 사용하는 것에 대한 일종의 보상이죠. (앞서 설명한 POW 개념입니다.)

하지만 이 보상을 받기 위해 블록 생성자들끼리 경쟁을 하고, 고성능의 컴퓨팅 파워가 더 유리한 위치를 차지할 수 있습니다. 채굴자들은 이런 이유로 하드포크 시에 새로운 가상화폐를 찍어내고 거기에 가치를 부여하려고 합니다. 이더리움 클래식이 그렇고, 비트코인 캐시가 그렇습니다.

이렇게 찍어낸 가상화폐에 가치를 부여하는 것이 맞는가에 대한 논란이 많지만, 현재까지는 돈이 가상화폐에 몰리고 있는 관계로 정통성(?)과는 관계없이 모두 거래가 되고 있습니다.

이런 문제 때문에 스팀을 개발한 댄 라이머(Dan Larimer, @dantheman)는 스팀에 증인 시스템을 도입했습니다.

커뮤니티 이용자들의 투표를 통해 20명의 증인을 선발합니다. 그리고 이 증인들은 새로운 블록 생성을 위한 컴퓨팅 파워를 제공하고, 커뮤니티의 중요한 결정에 제안을 하거나 환율(SBD-Steem) 결정을 하는 등의 영향을 끼칩니다. **증인들이 컴퓨팅 파워를 제공하는 것에 대한 보상으로 신규 발행량의 10%를 증인들에게 지급합니다.**(엄청나게 매력적인 보상이기 때문에 증인 후보자들은 어떻게든 20명의 증인 안에 들기 위해 최선의 노력을 다하게 됩니다.)

witness는 총 100명이 되고, 이 중 20명은 정규직, 80명은 비정규직이 됩니다. 20명은 1분마다 채굴을 하고, 나머지 80명은 20사람이 놓친 것이나 띄엄띄엄 나오는 것을 채굴하게 됩니다. 긴급 대기조 인 셈이지요. 

#### 증인 투표의 중요성

스팀파워의 또다른 활용은 증인 선출에 있습니다. 증인들은 스팀 네트워크 유지 뿐 아니라 각종 설정값을 조정할 수 있는 권한을 가지고 있습니다. 증인이 현명하게 행동하면 스팀 네트워크가 건강해지지만, 그렇지 못한 증인이 많아진다면 스팀이 해를 입을 수도 있습니다.

## 그런데 말이야.. 그래서 돈은 누가 주는 건데?

여기 한 광부가 있습니다. 열심히 금을 캡니다. 금을 캐는 이유는 간단합니다. 금을 시장에 가져가면 돈이 되기 때문입니다. 금은 한정된 자원이며, 금을 구매하고 싶은 사람들로 인해 시세가 정해집니다. 금은 귀금속입니다.

스팀잇을 대입해보죠.

여기 한 스티미언이 있습니다. 열심히 글을 씁니다. 글을 쓰면 스팀이라는 포인트를 준다고 하네요. 그리고 스팀은 시장에 가져가면 돈이 됩니다. 스팀도 한정된 자원이고, 스팀을 구매하고 싶은 사람들로 인해 시세가 정해집니다. 스팀은 전자화폐입니다.

이제 사람들이 스팀을 사는 이유만 알게되면, 우리가 스팀을 채굴할 이유는 충분해집니다.

스팀을 사는 이유는 주식을 사는 이유와 같습니다. 투자로 인한 수익을 거두기 위해서죠. 사람들은 실생활에서 유용하지 않아도 '투자'의 수단이 되는 것은 사들입니다.

주식을 사는 이유가 그 회사의 경영권을 지배하기 위해서인가요? 주식의 기능이긴하지만, 주식을 사는 사람들의 목적은 아닙니다. 스팀도 투자의 수단으로 거래소에 상장이 되어있고, 가치가 올라갔을때 팔기 위해 사람들이 매매하고 있습니다.

여기서 발생하는 것이 순환가치 입니다. ​
만약 돈을 좋아하는 어떤 사람이 하나의 화폐를 몽땅 소유했다고 가정해봅니다. 과연 그 화폐가 더이상 가치가 있을까요? 사람들은 계속 가치를 교환하길 원하고, 세상에는 새로운 화폐가 나와 그 수단이 될 것입니다. ​

스팀도 유통되지 않고 블로그에 갇혀있으면 아무리 많이 캐도 의미가 없습니다. 많은 폐쇄형 포인트들과 마찬가지 수준으로 전락합니다. 그러나 스팀은 전자화폐로서 현실화폐와 매우 능동적인 교환이 되기 때문에 의미를 가집니다. 따라서 캐서 팔면 삽니다. ​

### 그런데 스팀의 고유가치가 뭔데?

​많은 전자화폐들이 대부분 유한성과 무결성을 기본으로 하고, 특징적인 기능들로 시장을 유혹합니다. 기축통화격인 비트코인조차 선점효과로 화폐시장을 대표하고 있을 뿐, 특별한 고유가치를 갖고 있거나 하진 않습니다.

하지만 스팀은 고유가치가 있습니다. 스팀잇이라는 공유경제철학이 녹아 있는 커뮤니티가 있는 것이지요.

## 그래서 누가 얼마를 얻을 수 있는데?

### 보상 비율

먼저 스팀의 인플레이션율은 최초 오픈년 기준으로 년간 10%입니다. 매년 0.5%p 씩 줄어 올해는 현재 인플레이션율이 9.0%이고, 인플레이션율이 1%가 되면 그 이후로는 계속 1%로 유지됩니다. 약 2034년부터 1%가 됩니다.

그러니까 올해는 스팀의 양이 9.0% 증가한다는겁니다.

채굴량을 100%로 가정한다면, 각각의 보상 비율은 다음과 같습니다.
- 증인 : 10%
- 스팀파워 보유자 : 15%
- Reward Pool : 75% 
  - 저자 : 75% (56.25%)
  - 추천인 : 25% (18.75%)

전체 보상에서 증인 몫(10), 스팀파워이자(15)를 제외하고는 모두 일단 리워드 풀로 모이게 됩니다.   
이 리워드 풀은 총 양이 고정되어 있습니다. 왜냐하면 채굴되는 스팀의 양이 고정되어 있기 때문이죠.  
저자:큐레이션 비율 25%:75%는 곧 리워드 풀안에서의 비율을 말하는 겁니다.

이제, 여기에 늘어나는 인플레이션율에 각 배당받는 자들의 퍼센티지를 가져가면 그것이 스팀 배분의 비율이 됩니다.

스팀파워의 이자율이 1.5%라고 하는 것은, 인플레이션율의 15%가 스팀파워에 배당되고, 현재 인플레이션율이 약 10%이기때문에 10%의 15%는 1.5%가 됨으로 이자율이 1.5%가 되는 것입니다.

### 저자와 추천인 사이의 보상 변수

저자와 큐레이터(추천인), 이 두 대상에 대해 보상하는 방법이 보팅입니다.
다시말해 어떤 글에 보팅을 하면 일정 기간 경과 후(7일) 나를 포함하여 여러 사람들이 해당 글에 한 보팅 금액을 합산, 그 금액을 배분 원칙에 따라 저자와 보팅한 큐레이터들에게 보상으로 나누어주는거죠.

보팅에 관련된 보상 관련 변수는 크게 5가지 입니다.

- 글 등록 후 보팅까지 경과 한 시간
- 보팅 랭킹(어떤 글에 보팅을 몇번째로 했는가 하는거지요)
- 보유 스팀 파워 크기
- 보팅 파워 크기
- 보팅 비율

이렇게 5가지 요소가 복합적으로 상호 작용하면서 보상 금액이 결정되게 됩니다. 

세부 보상 체계는 다음과 같습니다.

- 보팅파워 : 1회 보팅 때마다 2%씩 차감
	- upvote 금액 = 스팀파워 x 보팅파워 x 보팅레이트 (https://steemnow.com/upvotecalc.html 에서 계산 가능)
	- 스팀파워가 높을 수록 보팅 한번에 큰 금액 보팅이 가능
	- 24시간 후 보팅 파워 20% 회복 (내 보팅 파워 확인 https://steemd.com/@id)
- 7일 후 해당 글 보팅 총액의 75%는 저자에게 25%는 큐레이터들에게 배분
	- 25% 배분 로직
	  - 보팅 선착순으로 차별 배분(배분 로직은 비공개)
	- 글 등록 15분 이내 보팅 : 저자에게 100%
	- 글 등록 15~30분 보팅 : 저자 50%, 큐레이터 50%
	- 글 등록 30분 이후~ 7일 보팅 : 큐레이터 100%


## 기타 관련 용어
### 풀보팅
보팅파워는 esteem어플에도 나오고, http://steemd.com/@본인ID 에서도 확인 가능한데, 100프로 풀보팅시 '잔여 보팅파워'의 2프로가 감소하며, 매 24시간마다 20프로(1시간에 약 0.83%)씩 회복합니다(잔여 보팅파워가 10%라면 24시간 뒤 30%, 잔여 보팅파워가 80%라면 24시간 뒤 100%).

이론상 하루 10회 풀보팅이 가능하다는 말이 나오는 것은 1회 풀보팅시 감소한 2%의 보팅파워가 2시간 24분(24시간의 1/10)이 지나야 완전히 회복되기 때문입니다.

100% > 풀보팅시 98% > 2시간 24분이 지나면 다시 100%. 이런 식으로 하루 10회 반복가능.

보팅의 가치는 보유한 스팀파워(SP)와 보팅파워에 비례하여 계산됩니다. SP가 많아 풀보팅시 20$가 찍히는 고래가 잔여 보팅파워가 50%인 상태에서 풀보팅한다면 그 보팅의 가치는 10$가 됩니다. 그 경우 보팅파워는 잔여 보팅파워 50%에서 2% 감소한 49%가 될테구요(=50% × (1 - 2%)).

(참고로 본인의 풀보팅가치는 http://steemnow.com/@본인ID 에서 확인가능합니다)

그런데 SP 500 이상 보유시 보팅 게이지를 통해 얼마만큼의 힘(Voting strength)으로 보팅할 것인지를 조절할 수 있습니다. 1회 풀보팅(100%)시 20$가 찍힌다고 가정할 때, 잔여 보팅파워가 100%인 상태에서 50%의 힘을 선택하여 보팅하는 경우에도 그 보팅의 가치는 10$가 되는 것입니다.

이 경우 보팅파워는 잔여 보팅파워 100%에서 2%의 절반인 1%가 감소한 99%가 될 것이며, 이렇게 보팅 힘을 50%로 조절한다면 개개의 보팅 가치는 절반으로 떨어지지만 회복하는 데 걸리는 시간 역시 절반으로 줄어들게 되므로, 보팅파워를 잃지 않고도 하루 20회의 보팅을 할 수 있게 됩니다.

33.33%의 힘을 사용시 30회, 25%의 힘을 사용시 40회.

그러나 횟수가 늘어나는 만큼 개별 보팅가치는 그만큼 줄어들게 되므로, 보팅가치를 모두 합하면 동일합니다.
(풀보팅시 20$ × 10회 = 200$. 보팅힘 50%조절시, 10$ × 20회 = 200$)

### 고래
고래란 스팀파워가 1000 메가 베스트인 유저들을 이르며, 일반적으로 스팀파워가 높은 유저들을 통칭합니다. [스팀잇보드](http://steemitboard.com/welcome.html)라는 서비스로 부터 유래되었습니다. 

* Red Fish = 0 ~ 10 메가 베스트
* Dolphin : 히어로((hero, 영웅) = 10 ~ 100 메가 베스트 
* Orca : 슈퍼 히어로(super hero) = 100 ~ 1000 메가 베스트
* Whale : 레전드((legend) = 1000 메가 베스트 이상

30일 이상 비활성화 상태가 된 계정은 죽은 물고기로 변합니다.ㅎㅎ
스팀잇보드는 스팀잇의 공식 서비스는 아니지만, 등급과 점수, 뱃지 등 게이미피케이션 요소를 활용하여 유저들의 커뮤니티 이용 활성화를 유도하고 있습니다. 

### 계급
스팀잇의 ‘최근 지불 통계 보고서’(일일 지급통계 보고서)에 따르면  사용자들의 계정은  7개 유형으로 분류됩니다.   

스팀잇에서 ‘최근 지불 통계 보고서’ 를 주기적으로 내고 있는 블로그 계정 운영자(@bitgeek)는 “계정의 레벨은 사용자가 갖고 있는 ‘스팀 파워’의 양에 따라 각기 다르다”고 밝혔습니다. ‘스팀 파워’의 별칭은 'vest'입니다. 즉 베스트는 스팀 파워를 부르는 다른 단위인 것입니다.  

구체적으로 보면 스팀잇 사용자 유형은 보유하는 스팀 파워에 따라 일곱 가지로 분류됩니다. 이에 따른 레벨은 맨 밑바닥인 ‘더스트'부터 최고봉인 '레전드'까지 모두 7가지 레벨이 존재합니다. 일종의 '(스티밋 내부의) 계급'인 셈입니다.    

오름차순으로 본 레벨은 ‘더스트(dust, 먼지) - 뉴비(newbie, 신참) - 유저(user, 사용자) - 슈퍼유저(superuser) - 히어로(hero, 영웅) - 슈퍼 히어로(super hero) - 레전드(legend)' 등입니다.  

각 레벨이 갖고 있는 ‘스팀 파워’ 즉 ‘vest’의 양<단위는 ‘메가 베스트’(mega vests)입니다> 은 다음과 같습니다.   

* 7등급 : 더스트(dust, 먼지) = 0 ~ 0.01 메가 베스트 -- Red Fish
* 6등급 : 뉴비(newbie, 신참) = 0.01 ~ o.1 메가 베스트 -- Red Fish
* 5등급 : 유저(user, 사용자) = 0.1 ~ 1 메가 베스트 -- Red Fish
* 4등급 : 슈퍼유저(superuser) = 1 ~ 10 메가 베스트 -- Red Fish
* 3등급 : 히어로((hero, 영웅) = 10 ~ 100 메가 베스트 -- Dolphin
* 2등급 : 슈퍼 히어로(super hero) = 100 ~ 1000 메가 베스트 -- Orca
* 1등급 : 레전드((legend) = 1000 메가 베스트 이상 -- Whale

메가(mega)는 ‘100만’이라는 뜻입니다. 개인의 베스트는 스팀잇의 ‘지갑’(wallet)에서 확인이 가능합니다. (steemd.com에 가보면 환산하는 공식을 알 수 있습니다.)

## 스팀잇 관련 주요 사이트
### 스팀잇 이용 관련 사이트
- http://steemitboard.com 스팀잇 점수와 등급, 뱃지 조회
- http://steemd.com 스팀 활동을 좀 더 기계적인 느낌으로, 소스나 필드명 등으로 볼 수 있는 사이트
- http://steemtools.com 스팀잇에 유용한 사이트나 툴들을 소개해주는 사이트
- http://www.steemitmeta.com 스팀과 스팀달러의 시세 조회
- http://steemstream.com 실시간 스팀잇 활동현황 알림
- http://steemwhales.com 이른바 고래라 불리는 스팀잇 최상위층의 순위와 정보
- https://steemstats.com 스팀잇 계정들의 여러 활동 조회
- http://steemstory.com 스팀잇 계정의 여러 정보를 다이나믹 시각화
- http://steempayout.com 자신의 포스팅이 받는 보상 안내
- https://steemkr.com KR태그 정리가 잘 되어 있음
- http://tool.steem.world/Post/Mentioned 자신을 언급한 글들을 확인 할 수 있는 사이트
- https://busy.org 스팀잇에 글을 올릴 수 있는 별도의 사이트. 올린 글에 대해서 그냥 보팅도 해줌.
- https://soboru.co.uk/steemme 스팀 활동 일목 요연한 정리 사이트
- https://steemviz.com/pendingpayouts Payout 시점 즉, 7일이 지나지 않은 글과 댓글에 대한 저자/큐레이션 보상 추정액 확인
- https://steemnow.com 본인의 스팀 활동 전반을 한 눈에 보여주는 사이트

- https://www.facebook.com/groups/197365584338716/ 스팀잇 사용자 모임 페이스북그룹
- http://m.dcinside.com/list.php?id=steemit#2 디시인사이드 스팀잇 마이너 갤

### 스팀잇 데이터 분석 소스 제공 사이트
- https://steemsql.com
- https://steemdb.com

## Next 스팀잇 표방 서비스

- 한국형 스팀잇 서비스, 메이벅스 http://www.maybugs.com/
- 탈중앙화 및 인센티브 기반 소셜 네트워크(TTC)기반 소셜네트워크, tataUFO https://www.ttc.eco/
- 개인 의료정보 공유 모델, 메디블록 https://medibloc.org/ko/
	- 메디블록 백서 요약 : https://steemit.com/medibloc/@ryugihyeok/medibloc-whitepaper
	- 메디블록은 스팀 기반은 아니지만 스팀잇의 보상체계를 의료정보 공유 모델에 차용

## 내가 관심가지고 보는 포인트
### 스팀잇의 가상경제구조를 통해 보는 CRM의 미래
이용자는 어떻게 자발적으로 커뮤니티(기업)의 가치 증대를 위해 기여하고, 그 기여에 대한 적절한 보상을 제공받으며, 커뮤니티(기업)은 그 경제 구조를 어떻게 운영할 수 있을 것인가. 

블록체인이라는 기술보다 Liquid와 vesting 개념을 기반으로 설계한 스팀잇의 가상경제 구조에 더 관심.

### 블록체인, 가상화폐 그리고 로열티 프로그램
- [Bitrewards](https://bitrewards.network/kr/)
- [일본 라쿠텐 자체 코인 발생 예정](http://biz.chosun.com/site/data/html_dir/2018/02/28/2018022801196.html)
- [LoyaltyX](https://www.loyaltyx.co/)
- [포인트 관련 블록체인, gatcoin](https://steemit.com/blockchain/@callihappiness/gatcoin)
	- 블록체인 혁명에서 말하는 블록체인이 적용될 수 있는 포인트 관련 업무는 바로 한정된 커뮤니티 안에서 로열티를 지급하여 그것이 기본적인 신뢰 포인트가 되게 할수도 있고 아니면 그것이 화폐 단위가 되게 하는 것이다. 현실의 예를 들으면 신한카드를 사용하면 사용 금액의 일정 비율을 포인트로 주는 것과 동일 하다. 하지만 그 포인트는 단지 신한카드를 쓸 때 사용할 수 있고 사용범위가 넓지 않다. 그런 점에서 겟 코인 일차적으로 이러한 포인트에 유동성을 주고자한다. 포인트에 유동성을 주는 것은 많은 사람들이 원하는 서비스이다.