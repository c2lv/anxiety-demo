# intro

`SceneSetup.intro();`

# intro-play-button

[<div class="mini-icon" pic="play1"></div> 시작! <div class="mini-icon" pic="play2"></div>](#intro-start) `publish("intro-to-game-1"); Game.OVERRIDE_CHOICE_LINE=true;`

# intro-start

(...500)

`clearText()`

n3: 띠용

`publish("show_options_bottom")`

# intro-start-2

`clearText()`

(...1000)

`publish("intro-to-game-2")`

n2: 이건 인간이다

(...600)

`clearText()`

(...300)

`publish("intro-to-game-3")`

# act1

`SceneSetup.act1();`

(...300)

n: 그리고 이건 인간의 불안이다

n: _당신_ 은 불안이다

[넌 점심을 혼자 먹고 있어! 또!](#act1a_alone)

[넌 먹는 동안 비생산적이야!](#act1a_productive)

[그 흰 빵은 너에게 해로워!](#act1a_bread)

# act1a_alone

`bb({mouth:"small", eyes:"narrow"})`

b: 너 외로움이 하루에 담배를 15개비 피우는 것만큼이나 조기 사망과 관련있다는 거 몰라?-

`Game.OVERRIDE_TEXT_SPEED = 2;`

`bb({mouth:"normal", eyes:"normal_right"})`

b: (홀트-룬스타드 외, 2010, 플로스 메디슨)

`hong({mouth:"0_neutral", eyes:"0_annoyed"})`

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
