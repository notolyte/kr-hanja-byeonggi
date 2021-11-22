# 漢字併記の韓国語を国漢文混用に変える機械
## リンク
[GitHub Pages](https://notolyte.github.io/kr-hanja-byeonggi/)
## 概要
[漢字路のテキスト変換機](http://hanjaro.juntong.or.kr/text_translater.aspx?hu=1)が私の環境だと調子を悪くしており，「韓国漢字/併記」以外の設定にするとエラーを吐くようになっていたので，「韓国漢字/併記」から「韓国漢字/変換」を容易に出力できるように簡単なツールをつくりました．第六共和国憲法前文を例とすると，例えば以下のように動作します．  

入力
> 유구(悠久)한 역사(歷史)와 전통(傳統)에 빛나는 우리 대한국민(大韓國民)은 3·1운동(運動)으로 건립(建立)된 대한민국임시정부(大韓民國臨時政府)의 법통(法統)과 불의(不義)에 항거(抗拒)한 4·19민주이념(民主理念)을 계승(繼承)하고, 조국(祖國)의 민주개혁(民主改革)과 평화적(平和的) 통일(統一)의 사명(使命)에 입각(立脚)하여 정의(正義)·인도(人道)와 동포애(同胞愛)로써 민족(民族)의 단결(團結)을 공고히 하고, 모든 사회적(社會的) 폐습(弊習)과 불의(不義)를 타파(打破)하며, 자율(自律)과 조화(調和)를 바탕으로 자유민주적(自由民主的) 기본질서(基本秩序)를 더욱 확고히 하여 정치(政治)·경제(經濟)·사회(社會)·문화(文化)의 모든 영역(領域)에 있어서 각인(刻印)의 기회(機會)를 균등히 하고, 능력(能力)을 최고도(最高度)로 발휘(發揮)하게 하며, 자유(自由)와 권리(權利)에 따르는 책임(責任)과 의무(義務)를 완수(完遂)하게 하여, 안으로는 국민생활(國民生活)의 균등(均等)한 향상(向上)을 기(期)하고 밖으로는 항구적(恒久的)인 세계평화(世界平和)와 인류공영(人類共榮)에 이바지함으로써 우리들과 우리들의 자손(子孫)의 안전(安全)과 자유(自由)와 행복(幸福)을 영원히 확보(確保)할 것을 다짐하면서 1948년(年) 7월(月) 12일(日)에 제정(制定)되고 8차(次)에 걸쳐 개정(改正)된 헌법(憲法)을 이제 국회(國會)의 의결(議決)을 거쳐 국민투표(國民投票)에 의(依)하여 개정(改正)한다.  
  
出力
> 悠久한 歷史와 傳統에 빛나는 우리 大韓國民은 3·1運動으로 建立된 大韓民國臨時政府의 法統과 不義에 抗拒한 4·19民主理念을 繼承하고, 祖國의 民主改革과 平和的 統一의 使命에 立脚하여 正義·人道와 同胞愛로써 民族의 團結을 공고히 하고, 모든 社會的 弊習과 不義를 打破하며, 自律과 調和를 바탕으로 自由民主的 基本秩序를 더욱 확고히 하여 政治·經濟·社會·文化의 모든 領域에 있어서 刻印의 機會를 균등히 하고, 能力을 最高度로 發揮하게 하며, 自由와 權利에 따르는 責任과 義務를 完遂하게 하여, 안으로는 國民生活의 均等한 向上을 期하고 밖으로는 恒久的인 世界平和와 人類共榮에 이바지함으로써 우리들과 우리들의 子孫의 安全과 自由와 幸福을 영원히 確保할 것을 다짐하면서 1948年 7月 12日에 制定되고 8次에 걸쳐 改正된 憲法을 이제 國會의 議決을 거쳐 國民投票에 依하여 改正한다.