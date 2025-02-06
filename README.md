## МУИС-ХШУИС-МКУТ Дадлагын тайлангийн жишээ загвар

### Documentation plan: 

```
intern-report
├─ .git
│  ├─ COMMIT_EDITMSG
│  ├─ FETCH_HEAD
│  ├─ HEAD
│  ├─ config
│  ├─ description
│  ├─ hooks
│  │  ├─ applypatch-msg.sample
│  │  ├─ commit-msg.sample
│  │  ├─ fsmonitor-watchman.sample
│  │  ├─ post-update.sample
│  │  ├─ pre-applypatch.sample
│  │  ├─ pre-commit.sample
│  │  ├─ pre-merge-commit.sample
│  │  ├─ pre-push.sample
│  │  ├─ pre-rebase.sample
│  │  ├─ pre-receive.sample
│  │  ├─ prepare-commit-msg.sample
│  │  ├─ push-to-checkout.sample
│  │  └─ update.sample
│  ├─ index
│  ├─ info
│  │  └─ exclude
│  ├─ logs
│  │  ├─ HEAD
│  │  └─ refs
│  │     ├─ heads
│  │     │  └─ main
│  │     └─ remotes
│  │        └─ origin
│  │           └─ main
│  ├─ objects
│  │  ├─ 05
│  │  │  └─ 099fc45df520256889fdc0dd93c06cb1effb3f
│  │  ├─ 09
│  │  │  └─ d2e432c43fe39581f51dde68d350a2eb755888
│  │  ├─ 0c
│  │  │  └─ 9cefc5937f31dbfa4d48078d945a8ce6b09a1e
│  │  ├─ 10
│  │  │  └─ ae32c3180d0abaca8b7e04b77ce819eab4a697
│  │  ├─ 17
│  │  │  ├─ 2d2e7c3d503b1f77290ea8fe3ffc74f767b062
│  │  │  └─ cda94e3c6eebbcc9722cc57532d07fa5302615
│  │  ├─ 1d
│  │  │  └─ 091fe9e504f8249c2ac35d45fddb5f6428196c
│  │  ├─ 20
│  │  │  └─ 1e4a53d1ad445b96ab0cb431dc5fc2d56c49b9
│  │  ├─ 21
│  │  │  └─ be4a242659a944d72d2b3f6ef5b0f3ebd90f08
│  │  ├─ 25
│  │  │  └─ 5b948e86aa10ee103fc335523208c37fc610f0
│  │  ├─ 26
│  │  │  └─ a9fe021dba7007303a012c4e011fa6e0c3811f
│  │  ├─ 29
│  │  │  └─ 062ad45018b715b949703ff371fb21dc69f6d7
│  │  ├─ 31
│  │  │  └─ 1fe03425b55692cd8b50fb4a9efea8780a81f8
│  │  ├─ 37
│  │  │  └─ 620c6401a16a596e4a027d281c64ce15fa17bf
│  │  ├─ 38
│  │  │  └─ 4a63d8e93a7863569c06cb80faf3aed88ff719
│  │  ├─ 3c
│  │  │  └─ 2eb71f7c15f9828caddd75fc025129f4e0d240
│  │  ├─ 43
│  │  │  └─ 522dcf80abff781ad168cdf22122ddadb713a8
│  │  ├─ 45
│  │  │  └─ ab1e6710bb11e59e8ff9025f9e718a39561989
│  │  ├─ 46
│  │  │  └─ 7602981d6cfdadc2bbbd9bfe8f9c24f2ab1004
│  │  ├─ 47
│  │  │  └─ 293f6c851314ff9576937ad9bb5f4acdd813b2
│  │  ├─ 4b
│  │  │  └─ a9ffbd918c18374250e47e6f8ced8d3c459266
│  │  ├─ 4c
│  │  │  └─ a04d6b62f1008d335eaf4d0aff85c5a9d87cb0
│  │  ├─ 53
│  │  │  └─ 9aaa735bb35c223ba3730d2a202c0c0129999c
│  │  ├─ 59
│  │  │  └─ 3a547e5d167a92310407f9f757722d9043a7d9
│  │  ├─ 5b
│  │  │  └─ 76b154bfec0a961be3d5849a7ce2a24b4ed558
│  │  ├─ 65
│  │  │  └─ 93bf638a5d374bf5b64fbf1022ee0341359a2f
│  │  ├─ 68
│  │  │  └─ eaaf5304ce445c5137c4838ba58ec93fa3f141
│  │  ├─ 6a
│  │  │  └─ 116ddde3f7bcbf0b3a2cdc1de3fe5877b0fefd
│  │  ├─ 6c
│  │  │  └─ b725710e07fd502a24f6575e6999b927c5e89c
│  │  ├─ 70
│  │  │  └─ 3e736e530c1a7470a7fc313786433f770a1968
│  │  ├─ 72
│  │  │  └─ 1a96527e90bc092d3876d406f6f333f7bca595
│  │  ├─ 73
│  │  │  └─ d7e16b695b8f2e5be5c2b0129ed492af70a5db
│  │  ├─ 75
│  │  │  └─ 3adcd38bdf9ff68dbb4d7206e836c1bfa1e929
│  │  ├─ 78
│  │  │  └─ b5757a3134fc45e281f7a8b6d929913bd25b71
│  │  ├─ 79
│  │  │  ├─ c638c6a7ff6ffc4b244cd16687d528962b59ee
│  │  │  └─ e4cb9006a268d50a80a9f4a3f1174b639da661
│  │  ├─ 7a
│  │  │  └─ cdfce86a76fd3c53b66f8858d85589da8a5b8e
│  │  ├─ 7c
│  │  │  └─ 846e2faa3ff9a3f2778deca258101e0a17e3e2
│  │  ├─ 81
│  │  │  └─ b52b39e1051b295c1bf1fe39b67223641160f9
│  │  ├─ 87
│  │  │  └─ b57b31318eaca5ec962c03a28d9ce5dd11c333
│  │  ├─ 88
│  │  │  └─ cdcd44d6fac84b8cff14d8c37d9d141164cec2
│  │  ├─ 89
│  │  │  ├─ 20413650ee8c1c05f7c43168a4f6ad6b238203
│  │  │  └─ 74be720d3f4e3c8cfd47f3d643f9d1e006ce08
│  │  ├─ 8d
│  │  │  ├─ 745b5437687f01fd1cb94d4e7eedb1ed90f13d
│  │  │  └─ 857aa43d2a707c35bbbabad090c5acb2cbe708
│  │  ├─ 90
│  │  │  └─ 3c0fcde2b857af23ef4f6d5e661462c80167bb
│  │  ├─ 99
│  │  │  └─ ba25e908f141f231057b039b7a931c9d3044cd
│  │  ├─ 9c
│  │  │  └─ d8d128b631e8de820d96d09a1c935a83cf9077
│  │  ├─ a0
│  │  │  └─ 15220250e5eb591533cade7dbf7b294e91dba8
│  │  ├─ ab
│  │  │  └─ 44afd650f6b251ed93a4c693f701ef1e2b8c9d
│  │  ├─ ad
│  │  │  └─ beb74aae49454576f1dad02e6a89616941ba68
│  │  ├─ b1
│  │  │  └─ 8a5125906e7e5feae98a4f7dd2ae20fa8fb8ad
│  │  ├─ b4
│  │  │  └─ 20e0b62b8ca3283568a980ac648d37c7b3a6db
│  │  ├─ bb
│  │  │  ├─ 221a0ea8da31dbde1d6054d60086b764f15535
│  │  │  └─ cd3c15a3f896d2c6bd17c9093368062f7e4f88
│  │  ├─ be
│  │  │  ├─ 1e511d78689337529397dd8d0506e003066a7c
│  │  │  └─ 724d7651b92255633a315ba74e902d2b9547db
│  │  ├─ bf
│  │  │  └─ fc1df3014e8e132d4ce749ffd5bba196f81eec
│  │  ├─ c0
│  │  │  └─ af84dcbb721200bb0fc0c84dc4f8453d353453
│  │  ├─ c3
│  │  │  ├─ a091b4ea73ac134d7af39e947f4f534cfa9dc3
│  │  │  └─ ba3944a3ac6c24eca49f9939fca0a445b6da6b
│  │  ├─ c4
│  │  │  └─ d5f89ccca10a64bb4db4e1ef3c5e4b6cd56fa8
│  │  ├─ c7
│  │  │  └─ 0f6afe7cb2e9d599e97e57be7ef0fb038919c1
│  │  ├─ c8
│  │  │  └─ c6645c5243e4179322725c0122b79286499d64
│  │  ├─ ce
│  │  │  └─ b4ba7212dca639f5f1344330fb8402191b001e
│  │  ├─ d6
│  │  │  ├─ 4b8849b4af71a738a79dff21bf47d732ac347a
│  │  │  └─ fc2ec10066077efebeac63b8127b4904ba0a47
│  │  ├─ e0
│  │  │  └─ 899215c0d8f7e3b2c0437f6071eb5937454a24
│  │  ├─ e5
│  │  │  └─ 2def6af4db32d02591ecfc749e4d88c08c0766
│  │  ├─ e6
│  │  │  ├─ 721b0d5decd205015047532ecd05b08bea7e32
│  │  │  └─ 9de29bb2d1d6434b8b29ae775ad8c2e48c5391
│  │  ├─ eb
│  │  │  └─ ecbaea97a10aa3d70a4175b93ddf15d378ccc7
│  │  ├─ ed
│  │  │  └─ e7f4085bf24bd18f05bc367be835d6dc906e46
│  │  ├─ ef
│  │  │  └─ aa5e85e857930f9c41970c703a432884f2386d
│  │  ├─ f1
│  │  │  └─ ea7e5d70cb4ad3693178d215ea2d52b69f41b0
│  │  ├─ f2
│  │  │  ├─ 276c949d66f92797dae26735880e38a009f33f
│  │  │  └─ 481c2afc20fb6eb47ff36bfefadbd648334aa7
│  │  ├─ f5
│  │  │  └─ 3adc4cd645bf828165d19e49ec625d04aa2aff
│  │  ├─ info
│  │  └─ pack
│  └─ refs
│     ├─ heads
│     │  └─ main
│     ├─ remotes
│     │  └─ origin
│     │     └─ main
│     └─ tags
├─ .gitignore
├─ .vscode
│  └─ settings.json
├─ README.md
├─ body.tex
├─ chapters
│  ├─ conclusion.tex
│  ├─ implementations
│  │  ├─ back.tex
│  │  ├─ front.tex
│  │  ├─ gorm.tex
│  │  └─ test.tex
│  ├─ introduction.tex
│  ├─ requirements.tex
│  └─ technologies.tex
├─ dics.sty
├─ images
│  ├─ .DS_Store
│  ├─ calendar.png
│  ├─ front.png
│  ├─ main.png
│  ├─ num-logo.png
│  ├─ review.jpg
│  ├─ role.png
│  └─ usecase-diagram.png
├─ important
│  ├─ abstract.tex
│  ├─ appendix.tex
│  ├─ bibliography.tex
│  ├─ main-pre.tex
│  └─ plan.tex
├─ main.ist
├─ main.locode
├─ main.tex
└─ writing.tex

```