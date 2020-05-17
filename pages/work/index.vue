<template>
  <main class="l-main">
    <article class="bl-article">
      <section class="bl-section">
        <div class="bl-media">
          <figure class="bl-media-img">
            <img src="~/assets/images/work.jpg" alt="work" />
          </figure>
          <div class="bl-media-body">
            <h2 class="el-heading2">Work</h2>
            <p>
              自身が持つデザインからエンジニアリングまでの幅広い業務経験を活かし、広い視野で問題解決に当たることを得意としています。
              また、仕事をするうえで大事にしているのは、個人プレーに走るのではなく、チームとして仕事に取り組むことです。
            </p>
          </div>
        </div>
      </section>

      <section class="bl-section">
        <h3 class="el-heading3">アパレル特化型ECサイトパッケージ開発</h3>
        <p class="bl-section-text">
          大規模ECモールとの在庫連動機能を持ったECサイトパッケージの開発
        </p>
        <section class="bl-section-narrow">
          <h4 class="el-heading4">担当フェーズ</h4>
          <p>フロントエンド構築・API実装</p>
        </section>
        <section class="bl-section-narrow">
          <h4 class="el-heading4">業務内容</h4>
          <p>設計・実装・進捗管理・教育</p>
        </section>
        <section class="bl-section-narrow">
          <h4 class="el-heading4">実績・取り組み等</h4>
          <p>
            外部ECカートベンダーとの共同開発部分について、インタフェース設計や開発者間の問い合わせ窓口対応を担当。加えて自社開発領域の設計及び実装・進捗管理を行い、
            特に開発効率向上のためのツール選定(npm,webpack系)や自動デプロイツールの開発(npm,shellスクリプト)、デザイナーとの協業による共通コンポーネント設計など工数削減施策を実施。
            メンバー教育・評価においては、日常的なコードレビューやペアプログラミングの他、定期的な1on1・目標設定・期末フィードバックを実施。
            ECサイト管理画面の開発ではデザインも含め設計・実装。(Nuxt.jsを利用)
            ECモールとの在庫連携用APIの一部について、インタフェース設計および実装。(Severlessフレームワークを利用しPythonで実装)
          </p>
        </section>
      </section>

      <section class="bl-section">
        <h3 class="el-heading3">大手アパレル系ECサイト リニューアル</h3>
        <p class="bl-section-text">
          国内有数の大手アパレル企業のECサイトフルリニューアル
        </p>
        <section class="bl-section-narrow">
          <h4 class="el-heading4">担当フェーズ</h4>
          <p>フロントエンド構築</p>
        </section>
        <section class="bl-section-narrow">
          <h4 class="el-heading4">業務内容</h4>
          <p>全体設計・実装・進捗管理・広告タグマネージャー導入</p>
        </section>
        <section class="bl-section-narrow">
          <h4 class="el-heading4">実績・取り組み等</h4>
          <p>
            自身の経験を活かし、デザイナー・バックエンドエンジニアとの連携・すり合わせを行い、品質と実装工数のバランスを見つつプロジェクトを進行。
            GoogleTagManagerを利用しECサイト内へ各種広告/解析タグを導入。解析に必要なデータを詳細に出力するためECカートのバックエンド処理の改修も担当。
            サイト内の各ページ・機能毎にパフォーマンスを計測し、ボトルネックとなっている箇所を検出。読み込み速度や実行速度の改善を行う。
            (例:DBに都度アクセスし、動的に出力されている箇所の静的出力バッチをNode.jsで構築など)
          </p>
        </section>
      </section>

      <section class="bl-section">
        <h3 class="el-heading3">その他</h3>
        <p class="bl-section-text">
          主にフロントエンドエンジニアとして、WEBサイト・ソーシャルゲーム・スマートフォンアプリ・デジタルサイネージなど多数開発。
        </p>
        <footer class="hp-txt-center">
          <nuxt-link to="/" class="el-link-more">もどる</nuxt-link>
        </footer>
      </section>
    </article>
  </main>
</template>

<script>
export default {}
</script>
