# GriefPrevention
建築物の保護機能を提供します。保護を行うことにより許可されたプレイヤー以外がブロックの破壊やレバーやボタンなどの操作をできなくします。

## 保護可能ブロック数
プレイヤーは初回ログイン時、500ブロックの保護が可能です。
サバイバルにログインすることにより、プレイ時間一時間当たり1000ブロック増加します。
これにより追加される最大ブロック数は10000ブロックです。

## 保護方法
「木のシャベル」を手にもって保護したいエリアの対角上の２ブロックを右クリックしてください。
X軸、Z軸の範囲のみで計算され、Y軸は0～256まで全てが保護されます。
保護範囲は最低100ブロック以上である必要があります。

!!! Info
    右クリックしたブロックは表示が「ダイヤモンドブロック」になり、保護に成功すると範囲が「金ブロック」及び「グローストーン」で囲まれます。

## 保護の削除方法
保護エリア内で`/AbandonClaim`もしくは`/unClaim`と入力することで削除することができます。

!!! Info
    `/AbandonAllClaims`と入力することで全ての保護エリアを削除できます。

## 保護エリア数の確認方法
`/Claimlist`で全ての保護エリアの座標及び、使用保護ブロック数の確認ができます。

## 他人と保護を共有する
共有したい保護エリアに立ち`/trust <プレイヤー名>`でプレイヤーに保護エリアを共有できます。
共有した人を確認したい場合は`/trustlist`で表示できます。

!!! Info
   `/AccessTrust <プレイヤー名>`でボタン、レバー、ベッドの使用許可を与える。
   `/ContainerTrust <プレーヤー名>`でボタン、レバー、ベッド、作業台、チェスト等の使用許可を与える。
   `/Trust <プレーヤー名>`でブロックの編集権限を与える。
   `/PermissionTrust <プレーヤー名>`で他のプレイヤーに共有する権限を与える。

## 保護エリアを分割する
保護エリアの一部のみ他のプレイヤーと共有したい場合や一部エリアのみ共有したくない場合などは`/subdivideclaim`と入力し「木のシャベル」で保護エリア内に更に保護エリアを作成できます。

!!! Info
    `/BasicClaims`で通常の保護エリア作成モードへ戻ることができます。

## 他人の保護エリアから抜け出す
他人の保護エリアから抜け出せなくなった場合`/Trapped`を入力し、その場で待っていると保護エリア外へテレポートされます。

## 保護されたMobを他人にあげる
保護されたMobを他人にあげる場合`/GivePet <プレーヤー名>`でプレイヤーにMobをあげる事が可能です。