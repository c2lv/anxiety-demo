# act1

`SceneSetup.act1();`

(...300)

n: 그리고 이건 인간의 불안이다

n: _당신_ 은 불안이다

`hong({mouth:"0_neutral", eyes:"0_annoyed"})`

h: 뭐 좋아요. 평화로운 분위기 속에서 먹기 *싫었는데*

`hong({eyes:"0_neutral"})`

n: 당신의 일은 *위험* 으로부터 인간을 보호하는 것이다

`bb({eyes:"look", mouth:"small_lock"})`

n: 사실, 저 샌드위치는 지금 인간을 *위험* 으로 몰아넣고 있다

n: 서둘러 경고해라!

`bb({eyes:"normal", mouth:"normal"})`

`Game.OVERRIDE_TEXT_SPEED = 1.25;`

n4: ( _당신_ 의 불안이 몸 밖으로 나왔다고 생각하고 당신에게 어떻게 말할 것 같은지 골라보세요! )

[넌 점심을 혼자 먹고 있어! 또!](#act1a_alone)

[넌 먹는 동안 비생산적이야!](#act1a_productive)

[그 흰 빵은 너에게 해로워!](#act1a_bread)

# act1a_alone

`bb({mouth:"small", eyes:"narrow"})`

b: 너 외로움이 하루에 담배를 15개비 피우는 것만큼이나 조기 사망과 관련있다는 거 몰라?-

`Game.OVERRIDE_TEXT_SPEED = 2;`

`bb({mouth:"normal", eyes:"normal_right"})`

b: (홀트-룬스타드 외, 2010, 플로스 메디슨)

`hong({eyes:"0_annoyed"})`

h: 음, 알려줘서 고맙지만--

`Game.OVERRIDE_TEXT_SPEED = 2;`

`bb({body:"fear", mouth:"normal", eyes:"fear"})`

b: 그러니까 지금 *당장* 누군가와 어울리지 않는다면 너는-

`bb({body:"panic"})`

b: 죽어어어어어어어어어어어어

```
bb({body:"normal", mouth:"normal", eyes:"normal"});
hong({mouth:"0_shock", eyes:"0_shock"});
attack("20p", "alone");
publish("hp_show");
```

(...2500)

`_.fifteencigs = true`

n: "불안"은(는) *사랑받지 못하는 것에 대한 두려움* 을 사용했다

(#act1b)

# act1a_productive

b: 후딱 노트북 꺼내서 뭐라도 당장 해!

`hong({eyes:"0_annoyed"})`

h: 음, 키보드에 빵 부스러기 묻히기 싫은--

```
bb({mouth:"normal", eyes:"fear"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: 네가 생산적이지 않다면 넌 무일푼 기생충이 될 테고 네 부모님은 이렇게 말하겠지

`bb({mouth:"small", eyes:"narrow"})`

b: "넌 우리 가족에게 불명예를 안겨줬다. 이제 우린 모두 할복해야 한다."

```
bb({body:"fear", mouth:"normal", eyes:"fear"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: 그럼 넌-

`bb({body:"panic"})`

b: 죽어어어어어어어어어어어어

```
bb({body:"normal", mouth:"normal", eyes:"normal"});
hong({mouth:"0_shock", eyes:"0_shock"});
attack("20p", "bad");
publish("hp_show");
```

(...2500)

`_.seppuku = true`

n: "불안"은(는) *나쁜 사람이 되는 것에 대한 두려움* 을 사용했다

(#act1b)

# act1a_bread

`hong({eyes:"0_annoyed"})`

h: 그거 검증된 거 맞--

```
bb({body:"fear", mouth:"normal", eyes:"fear"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: 가공된 밀은 혈당을 빨아들일 거고 너는 사지를 절단해야 하겠지. 그럼 너는-

`bb({body:"panic"})`

b: 죽어어어어어어어어어어어어

```
bb({body:"normal", mouth:"normal", eyes:"normal"});
hong({mouth:"0_shock", eyes:"0_shock"});
attack("20p", "harm");
publish("hp_show");
```

(...2500)

`_.whitebread = true`

n: "불안"은(는) *피해를 입는 것에 대한 두려움* 을 사용했다

(#act1b)

# act1b

n: 효과는 굉장했다!

`bb({mouth:"smile", eyes:"smile"});`

b: 나는야 최고의 보호자!

n: 하지만 당신은 아직 인간을 구하지 못했다

n: 인간의 체력 게이지를 모두 깎아라

n: 인간의 신체 + 사회 + 도덕적 욕구를 보호하기 위해 사용할 수 있는 건:

n: *피해를 입는 것* 에 대한 두려움 #harm#

n: *사랑받지 못하는 것* 에 대한 두려움 #alone#

n: 그리고 *나쁜 사람이 되는 것* 에 대한 두려움 #bad#

`Game.OVERRIDE_TEXT_SPEED = 1.25;`

n4: 꿀-팁: 지금 인간이 가장 깊고, 어두운 공포에 빠져있다고 생각하고 선택해라~

h: ...

```
hong({body:"putaway"});
sfx("rustle");
```

(...1000)

`Game.OVERRIDE_TEXT_SPEED = 1.5;`

h: 그냥 폰이나 볼래.

```
sfx("rustle2");
hong({body:"phone1", mouth:"neutral", eyes:"neutral"})
```

n: 인간을 보호해라

n: 세계로부터. 다른 사람으로부터. 그들로부터.

n: 행운을 빈다

(...500)

`Game.clearText()`

(...500)

(#act1c)

# act1c

`music('battle', {volume:0.5})`

n: ROUND ONE: *FIGHT!*

`bb({body:"normal", mouth:"normal", eyes:"normal"});`

h: 흠. 페북에 이번 주말에 파티가 있다고 하는데.

`bb({eyes:"uncertain"});`

b: *매번* 주말마다 파티를 여는 게 이상하지 않아?

`bb({eyes:"uncertain_right"});`

b: 분명 무언가가 있을 거야.

`hong({eyes:"surprise"});`

h: 근데, 나 초대받았다?

`bb({eyes:"narrow", mouth:"normal"});`

b: 그래 그렇다면!

[간다고 말해, 외로움으로 죽고 싶지 않으면](#act1c_loner)

[안 간다고 말해, 치명적인 마약으로 가득 차 있을 거야](#act1c_drugs)

[무시해, 넌 파티를 슬프게 만들 뿐이야](#act1c_sad)

# act1c_loner

{{if _.fifteencigs}}
b: 하루에 담배 15개비야, 인간. 15개비.
{{/if}}

{{if !_.fifteencigs}}
`Game.OVERRIDE_TEXT_SPEED = 1.5;`
{{/if}}

{{if !_.fifteencigs}}
b: 아무도 네 장례식에 나타나지 않을 거야. 네 재는 바다에 버려질거고. 그럼 넌 *고래밥*이 되겠지.
{{/if}}

{{if !_.fifteencigs}} `_.whalepoop = true` {{/if}}

(...500)

```
hong({mouth:"shock", eyes:"shock"});
attack("10p", "alone");
```

(...2500)

`bb({eyes:"normal"});`

{{if !_.fifteencigs}}
b: 그러니 넌 그 파티에 가야 해.
{{/if}}

{{if _.seppuku}}
b: 공부 좀 할 수 있게 노트북이나 가져 가.
{{/if}}

{{if _.whitebread}}
b: *흰 빵*을 대접받지 않는 한은.
{{/if}}

`hong({mouth:"anger", eyes:"anger"});`

h: 하. 널 입 다물게 할 수 있다면, 좋아.

h: 간다고 하겠어.

{{if _.whalepoop}}
b: 고래밥이라고, 인간. 고래밥.
{{/if}}

`_.partyinvite="yes"`

(#act1d)

# act1c_drugs

`bb({mouth:"small", eyes:"fear"});`

{{if _.whitebread}}
b: 아니면 그보다 더 나쁜... *흰 빵*
{{/if}}

{{if _.whitebread}}
`Game.OVERRIDE_TEXT_SPEED = 1.5;`
{{/if}}

{{if _.whitebread}}
b: 너는 흰 빵과 필로폰을 과다 복용하게 될 거야. 네 뚱뚱한 시체는 화장로에 들어가지 않겠지!
{{/if}}

{{if !_.whitebread}}
b: 너는 너무 많은 마약들을 과다 복용해서 장의사가 어떻게 네 몸이 *이미* 사전에 방부처리 되었는지 궁금해 할 거야!
{{/if}}

```
hong({mouth:"shock", eyes:"shock"});
attack("10p", "harm");
```

(...2500)

{{if _.seppuku}}
b: 또한 네가 파티에 갈 수 없다면 너는 부모님이 할복하지 않도록 공부해야 할 거야.
{{/if}}

`hong({mouth:"anger", eyes:"anger"});`

h: 하. 널 입 다물게 할 수 있다면, 좋아.

h: 안 간다고 하겠어.

`_.partyinvite="no"`

(#act1d)

# act1c_sad

`bb({eyes:"uncertain_right", mouth:"normal"});`

`Game.OVERRIDE_TEXT_SPEED = 1.5;`

{{if _.fifteencigs}}
b: 네가 할 수 있는 일은 외로움이 하루에 담배를 15개비 피우는 것만큼이나 치명적이라는 것에 대해 생각하며 구석에서 우는 것 뿐이야.
{{/if}}

{{if _.seppuku}}
b: 네가 파티에서 할 수 있는 일은 공부를 어떻게 해야 하는 지 걱정하는 것 뿐이야.
{{/if}}

{{if _.whitebread}}
b: 네가 할 수 있는 일은 건강에 좋지 않은 음식 선택이 너를 어떻게 해칠 지 걱정하는 것 뿐이야. 
{{/if}}

```
bb({mouth:"normal", eyes:"normal"});
hong({mouth:"neutral", eyes:"lookaway"});
```

h: 야, 너 나한테 왜 그래?

`hong({eyes:"neutral"});`

`Game.OVERRIDE_TEXT_SPEED = 1.5;`

b: 그래서 네가 간다면 사람들은 기분 나쁠 거야. 하지만 네가 초대를 거절하면 그 또한 기분 나쁘겠지!

`bb({body:"fear", eyes:"fear"});`

`Game.OVERRIDE_TEXT_SPEED = 1.5;`

b: 네가 하는 모든 일은 사람들을 기분 나쁘게 하니까, 넌 기분이 나빠야 해.

```
hong({mouth:"shock", eyes:"shock"});
attack("10p", "bad");
```

(...2500)

`hong({mouth:"anger", eyes:"anger"});`

h: 하. 널 입 다물게 할 수 있다면, 좋아.

h: 초대를 무시하겠어.

`_.partyinvite="ignore"`

(#act1d)

# act1d

```
bb({body:"normal", mouth:"normal", eyes:"normal"});
hong({mouth:"neutral", eyes:"annoyed"});
```

h: 어쨌든. 페북은 너무 과해. 뭔가 차분하고, 덜 불안하게 만드는 게 필요해.

`hong({eyes:"neutral"});`

h: 뭐 트위터에 새로운 것 없나?

`bb({eyes:"look"});`

[이런, 저 끔찍한 뉴스 좀 봐!](#act1d_news)

[이런, 저 트윗 *네* 뒷담화 아니야?](#act1d_subtweet)

[이거 봐, 우유 마시는 고양이 움짤이야](#act1d_milk)


# act1d_news

```
bb({eyes:"pained1"});
music(null, {fade:2});
```

b: 세상에, 세상이 타들어가는 것 같지 않아?

```
bb({eyes:"pained2"});
hong({mouth:"sad", eyes:"sad"});
```

b: 모든 게 끝나는 것 같아. 모든 게 죽어가는 것 같아. 우리는 망했고 우리가 할 수 있는 건 아무것도 없어.

```
Game.OVERRIDE_TEXT_SPEED = 0.5;
bb({mouth:"shut"});
```

b: ...

`bb({mouth:"smile", eyes:"smile"});`

b: 그거 리트윗하자!

```
hong({mouth:"shock", eyes:"shock"});
attack("10p", "harm");
```

(...2500)

`_.badnews=true`

```
music('battle', {volume:0.5});
hong({mouth:"anger", eyes:"anger"});
bb({body:"normal", mouth:"normal", eyes:"uncertain"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: 알았어 리트윗할게 제발 조용히 해!

`hong({mouth:"neutral", eyes:"annoyed"});`

h: 집어치우고, 스냅챗이나 보자.

(#act1e)


# act1d_subtweet

`bb({eyes:"fear"});`

b: 서브트윗이야! 교활하고, 교활한 서브트윗!

n: 역자: 서브트윗이란 트위터에서 특정 사용자를 직접 언급하지 않고 일반적으로 몰래 조롱 또는 비평하는 형태로 게시하는 게시물입니다.

`hong({eyes:"annoyed"});`

h: 아닐 거 같은데?

`bb({eyes:"narrow", mouth:"small"});`

b: 근데 만약 친구들이 모두 네 뒤에서 말하는 거라면

h: 걔네가 그럴 리가--

`bb({body:"fear", eyes:"fear", mouth:"normal"});`

b: *네 등 앞에서*

`hong({eyes:"sad", mouth:"sad"});`

h: 안 믿--

`bb({eyes:"narrow", mouth:"small"});`

b: 하지만 *만약에*

h: 그만--

`bb({eyes:"narrow_eyebrow"});`

b: *만약에*

```
Game.OVERRIDE_TEXT_SPEED = 0.5;
hong({mouth:"shut"});
```

h: ...

(...1000)

```
hong({mouth:"shock", eyes:"shock"});
attack("10p", "alone");
```

(...2500)

`_.subtweet=true`

```
hong({mouth:"anger", eyes:"annoyed"});
bb({body:"normal", mouth:"normal", eyes:"uncertain"});
```

h: 알-았어, 스냅챗 할 거야.

(#act1e)

# act1d_milk

`hong({mouth:"smile", eyes:"neutral"});`

h: 헤에 진짜 귀엽다! 바로 리트윗했어. 내 생각에--

```
hong({mouth:"shock", eyes:"shock"});
bb({body:"scream_anger"});
Game.OVERRIDE_TEXT_SPEED = 1.8;
```

b: *고양이는 우유를 소화하지 못하고 너는 동물 학대를 즐기는 끔찍한 사람이야.*

```
bb({body:"normal", mouth:"normal", eyes:"narrow"});
attack("10p", "bad");
```

(...2500)


`_.catmilk=true`

```
hong({mouth:"anger", eyes:"annoyed"});
bb({body:"normal", mouth:"normal", eyes:"uncertain"});
```

h: 알-았어, 스냅챗 할 거야.

(#act1e)

# act1e

`hong({mouth:"neutral", eyes:"neutral"});`

n4: 역자: 스냅챗은 미국 등에서 10대와 20대를 중심으로 큰 인기를 얻고 있는 SNS입니다.

h: 허, 어제 밤에 찍은 *사진들*. 주간 파티가 어땠는지 보여주네.

{{if _.partyinvite=="yes"}} (#act1e_said_yes) {{/if}}

{{if _.partyinvite=="no"}} (#act1e_said_no) {{/if}}

{{if _.partyinvite=="ignore"}} (#act1e_said_ignore) {{/if}}

# act1e_said_yes

`hong({mouth:"sad", eyes:"annoyed"});`

h: 이런, 너무 붐벼서 불안한데.

h: 초대에 응해서는 안 되는 걸까? 

```
hong({mouth:"neutral", eyes:"neutral"});
bb({mouth:"normal", eyes:"normal"});
```

[답을 바꾸겠다고? 이 믿을 수 없는 얼간이!](#act1e_yes_dontchange)

[답을 바꾸자! 너무 붐빈다!](#act1e_yes_changetono)

{{if _.subtweet}}
[그래 쟤들은 널 완전히 서브트위팅했어](#act1e_ignore_subtweet)
{{/if}}

{{if _.badnews}}
[잠깐 너 팩트-체크도 없이 그거 리트윗했어](#act1e_ignore_factcheck)
{{/if}}

{{if (!_.subtweet && !_.badnews)}}
[너 자세가 정말 안 좋은 거 알아?](#act1e_ignore_posture)
{{/if}}

# act1e_yes_dontchange

```
bb({eyes:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: 사람들은 네가 오기를 믿고 있었는데 이제 와서 그들의 믿음을 저버리겠다는 거야? 혼자 죽고 싶어?!

{{if _.fifteencigs}}
b: *15*. *담배*.
{{/if}}

{{if _.whalepoop}}
b: *고래*. *밥*.
{{/if}}

```
hong({mouth:"shock", eyes:"shock"});
attack("10p", "alone");
```

(...2500)

```
hong({mouth:"anger", eyes:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: 닥쳐 닥쳐 안 바꿔 갈 거야!

(#act1f)

# act1e_yes_changetono

```
bb({eyes:"fear"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: 너 군중 쇄도라고 아니?

```
bb({body:"fear", mouth:"small", eyes:"narrow"});
hong({eyes:"sad", mouth:"sad"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: 2003년 로드아일랜드 나이트클럽에서 화재가 발생했어. 공황 때문에 사람들이 출구를 막아버렸고 100명이 불에 타 죽었지-

```
bb({body:"normal", mouth:"normal", eyes:"fear"});
hong({mouth:"shock"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: 그런 일이 너에게 닥치길 원하니-

```
bb({body:"scream"});
Game.OVERRIDE_TEXT_SPEED = 2.5;
```

b: 가지 마 가지 마 가지 마 가지 마 가지 마 가지 마 가지 마 가지 마 가-


```
bb({body:"normal", eyes:"fear", mouth:"normal"});
hong({mouth:"shock", eyes:"shock"});
attack("10p", "harm");
```

(...2500)

```
hong({eyes:"anger", mouth:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: 닥쳐 닥쳐 바꿀 거야 안 갈 거야! 젠장!

(#act1f)

# act1e_said_no

`hong({mouth:"sad", eyes:"sad"});`

h: 흠... 정말 재미있어 보여.

h: 초대에 응할 수는 없는 걸까? 

`bb({mouth:"normal", eyes:"normal"});`

[답을 바꾸겠다고? 이 믿을 수 없는 얼간이!](#act1e_no_dontchange)

[답을 바꾸자! 혼자 죽지 마!](#act1e_no_changetoyes)

{{if _.subtweet}}
[그래 쟤들은 널 완전히 서브트위팅했어](#act1e_ignore_subtweet)
{{/if}}

{{if _.badnews}}
[잠깐 너 팩트-체크도 없이 그거 리트윗했어](#act1e_ignore_factcheck)
{{/if}}

{{if (!_.subtweet && !_.badnews)}}
[너 자세가 정말 안 좋은 거 알아?](#act1e_ignore_posture)
{{/if}}

# act1e_no_dontchange

`bb({eyes:"anger"})`

b: 모두들 널 믿고 있었어! ...내버려 둬, 너 없이 멋진 파티를 하게 놔 둬. 이 끔찍하고 역겹고 {{if _.whitebread}}}흰-빵-우적우적{/if}} 비열한--


```
hong({mouth:"shock", eyes:"shock"});
attack("10p", "bad");
```

(...2500)

```
bb({body:"normal", eyes:"uncertain", mouth:"normal"});
hong({mouth:"anger", eyes:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: 닥쳐 닥쳐 안 바꿔 안 갈 거야!

(#act1f)

# act1e_no_changetoyes

```
bb({body:"fear", eyes:"fear", mouth:"normal"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: 만성적 외로움은 코티솔을 증가시킬뿐만 아니라 심혈관 질환 및 뇌졸중 위험을 높여!

```
hong({mouth:"shock", eyes:"shock"});
attack("10p", "harm");
```

(...2500)

{{if _.fifteencigs}}
b: *15*. *담배*.
{{/if}}

```
bb({body:"normal", eyes:"normal", mouth:"normal"});
hong({mouth:"anger", eyes:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: 닥쳐 닥쳐 바꿀 거야 갈 거야! 젠장!

(#act1f)

# act1e_ignore_subtweet

```
bb({eyes:"fear", mouth:"small"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: 자업자득이야. 네 나쁜 트윗들이 다시 돌아온 거야!

```
bb({body:"fear", eyes:"fear", mouth:"normal"});
Game.OVERRIDE_TEXT_SPEED = 1.7;
```

b: 말실수 *한* 번만 해도 이른바 네 친구라는 것들은 좋아요를 받기 위해 널 거리에서 질질 끌고 다닐 거라고!

```
hong({mouth:"shock", eyes:"shock"});
attack("10p", "alone");
```

(...2500)

```
bb({body:"normal", eyes:"normal", mouth:"normal"});
hong({mouth:"anger", eyes:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: 왜 이러는 거야?!

(#act1f)

# act1e_ignore_factcheck

```
bb({eyes:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: 넌 가짜뉴스를 퍼뜨리고 있어!

```
bb({body:"scream_anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: 너 같은 사람들 때문에 민주주의 잔해에서 파시즘이 일어날 거라고!

```
bb({body:"normal", eyes:"anger"});
hong({mouth:"shock", eyes:"shock"});
attack("10p", "bad");
```

(...2500)

```
hong({mouth:"anger", eyes:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: 왜 이러는 거야?!

(#act1f)

# act1e_ignore_posture

```
bb({eyes:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: 등뼈가 프레첼마냥 구부러졌으면 좋겠어?! 당장 허리 펴!

```
bb({body:"meta"});
```

b: 그건 너도 마찬가지야.

```
bb({body:"normal", mouth:"normal"});
hong({mouth:"shock", eyes:"shock"});
attack("10p", "harm");
```

(...2500)

```
bb({body:"normal", eyes:"normal", mouth:"normal"});
hong({mouth:"anger", eyes:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: 왜 이러는 거야?!

(#act1f)

# act1e_said_ignore

`hong({mouth:"sad", eyes:"sad"});`

h: 흠... 정말 재미있어 보여.

h: 초대를 무시하지 말았어야 했나?

`bb({mouth:"normal", eyes:"normal"});`

[계속 무시해, 넌 여전히 갑분싸 메이커야](#act1e_ignore_continue)

[사실, 가고 싶었다고 말해](#act1e_ignore_changetoyes)

[사실, 가기 싫었다고 말해](#act1e_ignore_changetono)

# act1e_ignore_continue

`hong({eyes:"annoyed"});`

h: 하지만 계속 무시하는 건 좀 무례한 짓이야, 안 그래?

`bb({eyes:"normal_right"});`

b: 음 다른 사람들은 언제나 *너*를 무시하지 그래서

```
hong({mouth:"shock", eyes:"shock"});
attack("10p", "alone");
```

(...2500)

`bb({eyes:"normal"});`

b: 그럼 그냥 퉁치자.

(#act1f)

# act1e_ignore_changetoyes

`hong({eyes:"surprise", mouth:"smile"});`

h: 너... 날 즐겁게 내버려 둔다는 거야?

b: 뭐, 내 말은, 외로움은 널 *죽일 수* 있다는 거야.

`hong({eyes:"neutral", mouth:"neutral"});`

(#act1e_no_changetoyes)

# act1e_ignore_changetono

`bb({eyes:"narrow"});`

b: 많이 붐비네. 군중들이 위험하겠는걸.

(#act1e_yes_changetono)


# act1f

```
hong({mouth:"neutral", eyes:"neutral"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
```

h: 뭐 됐어. 새 틴더 알림이네.

n: 역자: 틴더는 2012년 서비스를 개시한 미국의 데이팅 앱입니다.

`bb({eyes:"uncertain"})`

b: 뭐, 그 원나잇 앱?

`hong({eyes:"annoyed"})`

h: 원나잇 앱 아니야, 그냥 새로운 사람을 만나는 방법ㅇ--

`bb({eyes:"narrow"})`

b: 원나잇 앱이야.

`hong({eyes:"surprise", mouth:"smile"})`

h: 오, 매칭 됐어! 귀여운데!

```
bb({eyes:"narrow_eyebrow"});
hong({eyes:"sad", mouth:"anger"})
```

h: 제발 날 위해 망치지 말아ㅈ--

```
bb({body:"panic"});
Game.OVERRIDE_TEXT_SPEED = 2.0;
```

b: 위험 위험 위험 위험 위험 위험 위험 위험 위험

`bb({body:"fear", eyes:"fear", mouth:"normal"})`

[넌 다른 사람들에게 *이용당하는* 거야.](#act1f_used_by_others)

[넌 그냥 다른 사람들을 *이용하는* 거야.](#act1f_using_others)

[*네 매칭 상대는 연쇄 살인범이야*](#act1f_killer)

# act1f_used_by_others

`bb({body:"point_crotch", eyes:"normal", mouth:"normal"})`

b: 랜덤 매칭으로 아마 네 성욕은 가득 채울 수 있을 거야.

b: 하지만 그걸론 절대 채울 수 없어.

`bb({body:"point_heart", eyes:"pretty", mouth:"small"})`

b: *마음의 구멍*을

(...3000)

```
bb({body:"normal", mouth:"normal", eyes:"normal"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: 요점은 넌 혼자 죽게 될 거란 사실이지

```
hong({mouth:"shock", eyes:"shock"});
attack("30p", "alone");
```

(...2500)

`_.hookuphole=true`

(#act1g)

# act1f_using_others

`bb({eyes:"narrow", mouth:"small"})`

b: 너 다른 사람의 성기를 네가 수집하는 포켓몬이라고 생각하는 거야?

```
bb({body:"sing", eyes:"pretty", mouth:"shut"});
music("pokemon");
Game.clearText();
Game.FORCE_CANT_SKIP = true;
```

```
Game.FORCE_TEXT_DURATION = 1000;
Game.FORCE_NO_VOICE = true;
```

b: ♫ (포켓몬 1기 엔딩곡)-

(...5600)

```
bb({mouth:"normal"});
Game.FORCE_TEXT_DURATION = 2400;
```

b: ♫ 나는야, 될 거야, 가장 헤-픈, 여자가-

(...500)

```
bb({eyes:"narrow", mouth:"small"});
Game.FORCE_TEXT_DURATION = 2100;
```

b: ♫ 허벅지, 엉덩이, 풍만한 젖가슴-

(...1500)

```
bb({eyes:"pretty"});
Game.FORCE_TEXT_DURATION = 2300;
```

b: ♫ 서로 생긴 모습은 달라도-

(...500)

```
bb({eyes:"fear", mouth:"normal"});
Game.FORCE_TEXT_DURATION = 2000;
```

b: ♫ 우리는 모두 친구!-

(...1000)

```
bb({eyes:"smile", mouth:"smile"});
Game.FORCE_TEXT_DURATION = 1000;
```

b: ♫ 땀에 젖은 탱탱볼, 막대ㄱ-

```
Game.FORCE_CANT_SKIP = false;
Game.clearText();
music(false);
bb({body:"normal", mouth:"normal", eyes:"normal"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: 요점은 네가 교활한 계집애란 사실이지

```
hong({mouth:"shock", eyes:"shock"});
attack("30p", "bad");
```

(...2500)

`_.pokemon=true`

(#act1g)

# act1f_killer

`Game.OVERRIDE_TEXT_SPEED = 1.5;`

{{if _.whitebread}}
b: 그 사람은 널 우물 속에 가두어 놓고 흰 빵을 강제로 먹이고 살찌게 해서 네 몸 가죽을 옷처럼 입을 수 있겠지!
{{/if}}

{{if _.seppuku}}
b: 그 사람은 뽀모도로 타이머로 널 때리고 네 배를 갈라 열며 이렇게 말하겠지 "이거나 받아라 게으름뱅이, *할복*"
{{/if}}

{{if !_.whitebread && !_.seppuku}}
b: 그 사람은 네 살을 갈기갈기 찢어버리고, 내장을 개울로 만들고, 피를 펀치볼에 섞을 거야! 
{{/if}}

{{if !_.whitebread && !_.seppuku}}
b: 파티에 초대하는 건 어때?!
{{/if}}

```
hong({mouth:"shock", eyes:"shock"});
attack("30p", "harm");
```

(...2500)

`_.serialkiller=true`

(#act1g)

# act1g

```
bb({body:"normal", mouth:"normal", eyes:"look"});
hong({body:"2_tired"});
Game.OVERRIDE_TEXT_SPEED = 0.5;
music(false);
```

h: ...

(...500)

h: 이 게임에 질렸어.

(...700)

`Game.OVERRIDE_TEXT_SPEED = 1.5;`

h:
{{if _.fifteencigs}}"외로움은 널 죽일 거야"... {{/if}}
{{if _.seppuku}}"생산적인 사람이 되거나 명예에 먹칠을 하거나"... {{/if}}
{{if _.whitebread}}"먹지 마, 그건 너를 죽일 거야"... {{/if}}
{{if _.subtweet}}"그들은 네 등 뒤에서 이야기하고 있어"... {{/if}}
{{if _.badnews}}"세계가 불타고 있어"... {{/if}}
{{if _.hookuphole}}"넌 혼자 죽을 거야"... {{/if}}
{{if _.serialkiller}}"그들은 연쇄 살인마야"... {{/if}}
{{if _.catmilk}}"고양이는 우유를 소화하지 못해"... {{/if}}
{{if _.pokemon}}쓰레기 같은 패러디 곡... {{/if}}

h: 난 그냥 내 삶을 살고 싶어.

h: 난 그냥 이 모든... 고통으로부터 자유로워지고 싶어.

`bb({eyes:"look_sad"});`

b: 이봐... 인간...

`Game.OVERRIDE_TEXT_SPEED = 0.5;`

b: 괜찮을 거야.

(...600)

`bb({body:"point_heart", eyes:"look_sad_smile", mouth:"smile"});`

b: 너의 충실한 보호자로서, 나는 항상 위험을 살펴보고, 너를 안전하게 지키기 위해 최선을 다 할 거야.

`bb({body:"normal", eyes:"look_sad", mouth:"smile"});`

b: 약속할게.

(...600)

```
bb({body:"normal", eyes:"normal", mouth:"normal"});
hong({body:"phone1", eyes:"neutral", mouth:"neutral"});
```

h: 마지막 앱. 인스타그램. 어떤 게 있지?

`hong({eyes:"sad"});`

h: 이건... 더 많은 파티 사진이네.

`hong({mouth:"sad"});`

h: 모두들 정말 행복해보여. 걱정 없이. 불안 없이.

`hong({mouth:"anger"});`

h: 젠장, 왜 나는 저렇게 될 수 없는 거야? 왜 나는 *평범*할 수 없지?

`bb({eyes:"normal_right"});`

b: 파티 얘기가 나와서 말인데, 이번 주말 초대에 대해서. 내 최종 결정은 이래.

`bb({eyes:"normal"});`

[넌 가야 해.](#act1g_go) `Game.OVERRIDE_CHOICE_LINE=true`

[넌 가지 말아야 해.](#act1g_dont) `Game.OVERRIDE_CHOICE_LINE=true`

# act1g_go

`_.act1g = "go"`

(#act1h)

# act1g_dont

`_.act1g = "dont"`

(#act1h)

# act1h

b: 넌 가--

```
bb({eyes:"wat", mouth:"small"});
hong({body:"2_fuck"});
```

h: *닥.*

`hong({body:"2_you"});`

h: 쵸.

(...500)

b: ㅁ

(...1500)

`bb({eyes:"wat_2"});`

b: 뭐?

`hong({body:"phone1", eyes:"anger", mouth:"anger"});`

h: 난 파티에 갈 거야

{{if _.act1g=="go"}}
h: 네가 원해서가 *아니라*, *내*가 원해서야.
{{/if}}

{{if _.act1g=="dont"}}
h: 정확히 *왜냐하면* 넌 내가 가지 않길 원하니까.
{{/if}}

```
hong({body:"putaway"});
sfx("rustle");
```

h: 넌 날 통제할 수 *없어*.

```
sfx("rustle2");
hong({body:"0_sammich", eyes:"0_annoyed", mouth:"0_neutral"});
```

h: 이 맛있는 샌드위치를 빌어먹을 평화 속에서 먹을 동안 실례 좀 할게.

`hong({body:"2_sammich_eat"});`

(...601)

```
sfx("sandwich");
hong({body:"2_sammich_eaten", eyes:"0_lookaway", mouth:"0_chew1"})
```

(...601)

```
bb({body:"normal", eyes:"uncertain", mouth:"shut"});
Game.OVERRIDE_TEXT_SPEED = 0.5;
```

b: ...

```
bb({eyes:"normal_right"});
Game.OVERRIDE_TEXT_SPEED = 1;
```

b: ...

```
bb({eyes:"fear"});
Game.OVERRIDE_TEXT_SPEED = 4;
```

b: ..................

(...500)

`bb({mouth:"normal"});`

[아아아아아 우린 죽을 거야](#act1h_death) `Game.OVERRIDE_CHOICE_LINE = true;`

[아아아아아 모두가 우릴 싫어해](#act1h_loneliness) `Game.OVERRIDE_CHOICE_LINE = true;`

[아아아아아 우린 끔찍한 사람이야](#act1h_worthless) `Game.OVERRIDE_CHOICE_LINE = true;`

# act1h_death

```
bb({body:"fear"});
Game.OVERRIDE_TEXT_SPEED = 3;
```

b: 아아아아아 우린 죽을 거야 아아아아아아아아아아아

```
hong({body:"3_defeated1"});
attack("100p", "harm");
```

(...2500)

(#act1i)

# act1h_loneliness

```
bb({body:"fear"});
Game.OVERRIDE_TEXT_SPEED = 3;
```

b: 아아아아아 모두가 우릴 싫어해 아아아아아아아아아아아

```
hong({body:"3_defeated1"});
attack("100p", "alone");
```

(...2500)

(#act1i)

# act1h_worthless

```
bb({body:"fear"});
Game.OVERRIDE_TEXT_SPEED = 3;
```

b: 아아아아아 우린 끔찍한 사람이야 아아아아아아아아아아아

```
hong({body:"3_defeated1"});
attack("100p", "bad");
```

(...2500)

(#act1i)

# act1i

```
bb({mouth:"smile_lock", eyes:"smile", body:"normal"});
music('battle', {volume:0.5});
```

n: 축하합니다

(...500)

n: 당신은 인간의 안전, 사랑, 선량함에 대한 욕구를 성공적으로 보호했습니다

n: 와우, 인간이 얼굴로 어마어마한 감사를 표현하고 있군요!

(...500)

n: 이제 인간의 체력은 전혀 없고, 당신은 인간의 행동을 직접 통제할 수 있습니다

`bb({mouth:"smile", eyes:"normal"});`

n: 마지막 행동을 선택하세요

`bb({mouth:"normal", eyes:"narrow"});`

n: *끝장내세요*

[{FIGHT: 짜증나는 폰을 혼내주자!}](#act1i_phone) `Game.OVERRIDE_CHOICE_LINE=true`

[{FLIGHT: 몸을 웅크리고 울어!}](#act1i_cry) `Game.OVERRIDE_CHOICE_LINE=true`

# act1i_phone

`bb({eyes:"anger", mouth:"normal"})`

b: 네 폰이 너에게 공황 발작을 일으켰어!

```
bb({body:"fear", eyes:"fear"});
hong({body:"3_defeated2"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: 혼내 줘! 폰을 부숴버려! 죽여버려!

```
Game.OVERRIDE_TEXT_SPEED = 2.5;
bb({body:"flail"});
hong({body:"3_defeated3"});
_.act1_ending = "fight";
```

b: 죽여버려 죽여버려 죽여버려 죽여버려 죽여버려 죽여버려 죽여버려 죽여버려 죽여버려 죽여버려 죽여버려 죽여버려 죽여버려 죽여버려 죽여버려 ㅈ--

(#act1j)

# act1i_cry

`bb({eyes:"fear"})`

b: 온 세상이 위험으로 가득 차 있어!

```
bb({body:"fear"});
hong({body:"3_defeated2"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: 람머스처럼 행동해! 자기-방어를 위해 몸을 웅크려!

```
Game.OVERRIDE_TEXT_SPEED = 2.5;
bb({body:"flail"});
hong({body:"3_defeated3"});
_.act1_ending = "flight";
```

b: 웅크리고 울어 웅크리고 울어 웅크리고 울어 웅크리고 울어 웅크리고 울어 웅크리고 울어 웅크리고 울어 웅--

(#act1j)

# act1j

`SceneSetup.act1_outro()`