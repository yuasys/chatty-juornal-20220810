# chatty-juornal-20220810

<details>
<summary><h2>今日の取り組み</h2></summary>

1. githubを活用した学習方法の研究開発（前日から継続中）
    - かなり慣れが必要と思うしばらく試行錯誤してみる

2. フロントエンド開発に何が一番必要か検討した

3. メール処理業務
    - 毎日結構な作業量になるので改善が必要だ。
  
4. 既存のHTML,CSS,Javascriptコード研究

    - 他の方がどのような書き方をしているか見るだけでかなり役立つ
    - 理想形を追求して真似するのが一番必要かと思う
    - 今日は前からあこがれていた[サイト](https://sdgs.edutown.jp/)のソースの美しさに打たれた
    
</details>

<details>
<summary><h2>今日の気づき</h2>
</summary>
1. GTM(Google Tag Manager)をそのままReact系フレームワークNextJSに適用しても意味がない。GTMの代わりとなる別のアプローチが必要。  

<br/>Example Code [出典](https://sdgs.edutown.jp/) 
    <!-- Google Tag Manager -->
    <script>
        (function(w, d, s, l, i) {
            w[l] = w[l] || [];
            w[l].push({
                'gtm.start': new Date().getTime(),
                event: 'gtm.js'
            });
            var f = d.getElementsByTagName(s)[0],
                j = d.createElement(s),
                dl = l != 'dataLayer' ? '&l=' + l : '';
            j.async = true;
            j.src =
                'https://www.googletagmanager.com/gtm.js?id=' + i + dl;
            f.parentNode.insertBefore(j, f);
        })(window, document, 'script', 'dataLayer', 'GTM-MXNGFFP');
    </script>
    <!-- End Google Tag Manager -->
   ```
</details>

