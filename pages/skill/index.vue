<template>
  <main class="l-main">
    <article class="bl-article">
      <section class="bl-section">
        <div class="bl-media">
          <figure class="bl-media-img">
            <img src="~/assets/images/skill-frontend.jpg" alt="skill" />
          </figure>
          <div class="bl-media-body">
            <h2 class="el-heading2">Skill</h2>
            <p>
              Web系フロントエンド領域のエンジニアリングを中心として、デザイン・バックエンドなど幅広い業務を経験。
              インターネット広告分野の黎明期にはFlashを用いたブランディングサイト構築などを多数経験。
              Webトラフィックの主軸がスマートフォンに移ったのちは、主にJavaScript/HTML5/CSS3による開発へ移行。
            </p>
          </div>
        </div>
      </section>

      <section class="bl-section">
        <h3 class="el-heading3">フロントエンド</h3>
        <p>
          フロントエンド開発はECMAScript2020相当のJavaScriptで記述。Babelを利用し、ECMAScript2015互換へ変換。webpackを用いてプロダクトに応じて適切な粒度にパッケージングしたビルド設定を行う。
          CSSはSass(Scss)を利用し記述。webpackにPostCSS・Autoprefixerモジュールを適用し、プロダクトの動作保証ブラウザバージョンに応じた出力設定を行っている。
          CSS設計はプロダクトの規模やメンバーの習熟度、ライフサイクルにより、OOCSS,SMACSS,ITCSS,PRECSSなどを使い分け、必要に応じてアレンジする。
          近年は特にVue.jsやNuxt.jsを利用して開発する頻度が高い。
        </p>
        <div class="bl-description">
          <dl>
            <dt>言語</dt>
            <dd>JavaScript</dd>
            <dd>HTML5</dd>
            <dd>CSS3/Sass</dd>
            <dd>ActionScript</dd>
            <dd>Objective-C</dd>
          </dl>
          <dl>
            <dt>フレームワーク</dt>
            <dd>Vue.js</dd>
            <dd>Nuxt.js</dd>
            <dd>jQuery</dd>
            <dd>AngularJS</dd>
            <dd>Flash</dd>
          </dl>
        </div>
      </section>

      <section class="bl-section">
        <h3 class="el-heading3">バックエンド</h3>
        <p>
          主業務ではないものの、API実装やマーケティング用のデータ出力、障害やボトルネック発生時の調査対応など必要に応じてバックエンド領域の開発も経験。
        </p>
        <div class="bl-description">
          <dl>
            <dt>言語</dt>
            <dd>Python</dd>
            <dd>Java</dd>
            <dd>PHP</dd>
            <dd>Perl</dd>
            <dd>VBScript</dd>
          </dl>
          <dl>
            <dt>フレームワーク</dt>
            <dd>Serverless</dd>
            <dd>Nasp</dd>
            <dd>Symfony</dd>
          </dl>
          <dl>
            <dt>データベース</dt>
            <dd>DynamoDB</dd>
            <dd>MySQL</dd>
            <dd>SQLServer</dd>
          </dl>
        </div>
      </section>

      <section class="bl-section">
        <h3 class="el-heading3">ツール</h3>
        <p>
          プロジェクト規模に応じたGit-Flowの立案・社内教育などGit運用について多くの経験を積む。
          また、簡易なデザインや素材加工などのためAdobe系デザインツールの利用が可能。
          バックエンド開発のため各種AWSツールを利用している。
        </p>
        <div class="bl-description">
          <dl>
            <dt>VCS/パッケージ管理/ビルド/その他</dt>
            <dd>Git/Github</dd>
            <dd>Node.js</dd>
            <dd>npm</dd>
            <dd>webpack</dd>
            <dd>GoogleTagManager</dd>
          </dl>
          <dl>
            <dt>プロジェクト管理・コミュニケーション</dt>
            <dd>G Suit</dd>
            <dd>Backlog</dd>
            <dd>Jira</dd>
            <dd>Slack</dd>
          </dl>
          <dl>
            <dt>デザイン</dt>
            <dd>Photoshop</dd>
            <dd>Illustorator</dd>
            <dd>Sketch</dd>
            <dd>Abstract</dd>
          </dl>
          <dl>
            <dt>AWS</dt>
            <dd>lambda</dd>
            <dd>CloudWatch</dd>
            <dd>CodeBuild</dd>
            <dd>CloudFormation</dd>
            <dd>Cognite</dd>
            <dd>S3</dd>
            <dd>elasticSearch</dd>
          </dl>
        </div>
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
