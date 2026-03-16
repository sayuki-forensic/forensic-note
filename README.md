# Forensic Notes
**Aspiring International Forensic Analyst / CFE Candidate / Digital Forensics & Fraud Investigation**

---

## 2026-03-12 0 Day 1

### What I did today
- Registered on CyberDefenders
- Opened the first forensic challenge
- Published this repository

### What I found
- Could not understand the challenge at all
- English and technitial terms were completely unfamiliar
- Realized I need to build foundational knowladge first

### Next steps
- Learn basic Python (hash verification scriipt)
- Build English vocabulary for forensic terms
- Study fundamental concepts before attempting challenges

---

## 2026-03-13 - Day 2

### 今日読んだ記事
- OCCRPへの批判に対するOCCRPによる回答記事

### 批判した側の属性
- petriot（愛国者）
- skeptic（懐疑主義者・陰謀論者）

### 批判の内容
- 西洋諸国・政府・団体のpolitical tool（駒）だというレッテル
- 政権転換を狙うpolitical activism（政治活動）だという疑い
- 反対勢力攻撃のための機関だという疑い

### OCCRPの反論
- 様々な国の金融機関・弁護士・首相・大統領の不正を暴いた実績
- EUや団体からの寄付金はあるがreporting（報道内容）への関与はない
- sponsorについて明示している

### 私の見解
正論だけでは解決しない。

批判した側に悪意があるとは限らない。人はlogicではなくemotionで動く。
どれだけ正確なfactを並べても、愛国者は母国を守るというbeliefがevidenceより優先されるし、懐疑心が強い人は疑い続ける。

conspiracy theory（陰謀論）はdramaticで分かりやすくemotionalだ。
それに比べて、factは無機質で複雑で難解だ。
感情優位の人間に複雑なfactを提示しても、曲解してさらに思想が歪む。

### 課題
感情・感覚が優位の人間に対して、難解なfactとevidenceをどうわかりやすく伝えるか。
これはforensic reportの伝達設計にも直結する課題だ。


### 分析レポート（まとめ） -　OCCRP批判への考察

#### 1. 構造化された対立
OCCRPを巡る攻防は単なる「事実vs嘘」の争いではない。
批判側（愛国者・懐疑主義者）はOCCRPを「西側のpolitical tool」「政権転換を狙う政治工作機関」と定義した。
OCCRPは「実績」「資金のtransparency（透明性）」「編集のindependence（独立性）」で反論した。

#### 2. なぜ正論は届かないのか
- 愛国心というfilter：母国の正当性を守りたいという正義感で動く
- 陰謀論のentertainment性：factは無機質で複雑だがconspiracy theoryはdramaticで分かりやすい
- Backfire effect（バックファイア効果）：疑念が強い人間に複雑なevidenceを提示すると、「巧妙な隠蔽」と曲解されて思想がさらに強化される

#### 3. フォレンジック的課題
感情優位の層に対していかに難解なfactを、彼らのsensibilityを損なわずにdeliverするか。
evidenceを検証する力（forensic）に加えて、情報を構造的に正しく伝えるinterfaceの設計が鍵になる。

---


## 2026-03-14 - Day 3 

### 今日読んだ記事
中国・ロシア・北朝鮮の三角関係についての記事

### 事実
- 中国がロシアと協力関係にある北朝鮮との関係強化に動いた
- 三カ国とも反米側で自己完結する動きをとっている
- ロシアとベネズエラでも西側を介さない内密な取引が行われていた
- BRICSの拡大・SWIFT迂回経済網の構築が進行中

### 構造分析
- 三カ国の目的：制裁・情報漏洩リスクを減らすためのblackbox化
- 中国の戦略：世界を中国へのdependence（依存）で縛る
- 西側の対応：自給率促進・技術力・経済力で中国をcontrol下に置く
- 現状：お互いがdependし合う秩序が成立している

### forensicへの直結
- SWIFT迂回網＝制裁回避・マネーロンダリングの温床
- blackbox化が進むほどforensic調査の難易度が上がる
- 些細な違和感・矛盾の検出＝red flag（不正の予兆）の発見

### 私の見解
どの国も対等に深刻に扱うこと・孤立化させないことが重要だ。
独裁国家・反対勢力を安易に敵対視してはいけない。
世界の均衡が崩れると結果的に全員が損害を受ける。
forensic analystとして、独裁国家側のred flagにもいち早く気づける視点を持ち続ける必要がある。

### 今日の単語
- sanctions: 制裁
- red flag: 不正の予兆
- blackbox: 内部が見えない取引構造
- SWIFT: 国際銀行間送金ネットワーク

---


## 2026-03-15 - Day 4

### 読んだ記事
Reuters：AIによるSaaS業界終末論にソフトウェア各社が反論

### 事実
- AIによってSaaS需要が消えるという懸念が広がっている
- Microsoft・会計ツールなどがAIで代替されるという議論
- ソフトウェア各社は既存ツールの需要は消えないと反論

### 構造分析
- AIが得意なのはSaaSで作成できるレベルの成果物
- ソフトウェア会社は既存ツールのまま維持しない。AI統合で進化する
- 需要が消えるのはtoolではなくtoolをある程度使える中間層だ

### 私の見解
楽な方に流され、AIに使われる層が増えるだけだ。
AIに代替されるのは思考しない人間であって、高度な技術者はAIを道具として凌駕する手段を生み出す。

### forensicへの直結
- AIはforensic toolの精度を上げる道具になる
- AIに仕事を奪われる側ではなくAIを使いこなす側に立つ
- 中間層にならないために、私はCFE・GCFAの専門性を身に着けたい

### 今日の単語
- SaaS: インターネット経由で提供されるソフトウェアサービス
- disruption: 既存産業の破壊的変革
- obsolete: 時代遅れになる・陳腐化する

### 追記
- 責任を取れない：AIは判断の法的責任を負えない
- 信頼性とbrand：SaaSには積み上げてきた実績があり、AIには代替できないtrust（信頼）がある
- 曖昧さの処理：業務にはAIが苦手とするcontext（文脈）と judgment（判断）が必要な領域がある
- 業務は単純ではない：AIが全て代行できる程、人間の仕事は構造化されていない

---

## 2026-03-16　- Day 5

### 読んだ記事
Reuters：自衛隊の中東派遣・情報収集目的で政府検討・ホルムズ除外

---

### 1. Executive Summary
2026年3月16日
ホルムズ海峡封鎖および原油価格高騰に伴う、日本の国家戦略および経済的脆弱性の構造分析。

### 2. Strategic Dilemma
日本政府は極めて難易度の高い多面外交を遂行している。

対米戦略
- Action: 自衛隊の中東派遣（情報収集名目）
- 意図: 日米同盟維持・米側要求へのalibi提示
- Risk: イランからの敵視・軍事行動への巻き込み

対イラン戦略
- Action: ホルムズ直接通過を回避しつつ外交チャンネル維持
- 意図: 石油調達ルート確保・敵対回避
- Risk: 米国からの不信感・同盟弱体化

国内維持
- Action: 過去最大規模の石油備蓄放出・価格抑制パッチ
- 意図: エネルギー供給断絶による国家崩壊の延命
- Risk: 備蓄枯渇後の無策・長期インフレ

### 3. Root Cause & Long-term Solution
- 根本原因: エネルギー供給95%以上をアラビアに依存する　structural vulnerability（構造的脆弱性）
- 解決策: 米・独・中等との戦略的提携による、次世代エネルギー源の共同開発
- 現実的課題: 技術開発完了まで国家を延命させることが現在の最優先タスク

### 4. Personal Survival Protocol
**Financial Defense**
- 生活コストの極小化・貯金の積み増し
- 物価高騰に備えたリソース最適化

Skill Stack
- 簿記2級：コスト構造を見抜き企業の生存性を分析する力
- IT：インフラ構造の理解・情報の真偽を判定するリテラシー

Discipline
- 筋トレによる基礎体力の向上
- 緊急事態における冷静な判断力の維持

### 5. Commit Message
現状は極めて厳しいが、0.1%の可能性を掴み取るための自己アップデートを継続する。

### 今日の単語
- vulnerability: 脆弱性
- alibi: アリバイ・行動の正当化
- strategic dilemma: 戦略的ジレンマ
- energy security: エネルギー安全保障
