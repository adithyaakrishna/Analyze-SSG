# Static Site Generators

## Introduction:

<br />

There are many static site generators like VuePress, Docusaurus etc... but all of them have one single and specific goal, to generate static HTML file and all of its assets.

The advantages of using SSGs are,
- Faster Loading Time
- Secure
- Easier Caching
- Easier to Update (Depending on the SSG you tend to use)

<table>
  <tr>
    <th>Static Page</th>
    <th>Dynamic Page</th>
  </tr>
  <tr>
    <td><img align="center" src="https://raw.githubusercontent.com/adithyaakrishna/reimagined-system/master/assets/Static.png" /></td>
    <td><img align="center" src="https://raw.githubusercontent.com/adithyaakrishna/reimagined-system/master/assets/Dynamic-F.png" /></td>
  </tr>
</table>

## SSG Comparison:

<br />

<table>
  <tr>
    <th></th>
    <th>License</th>
    <th>Language</th>
    <th>Framework</th>
    <th>Focus</th>
    <th>Based&nbsp;On</th>
    <th>Hybrid</th>
    <th>Image&nbsp;Optimization</th>
    <th>Community</th>
    <th>Learning&nbsp;Curve</th>
    <th>Community Chat</th>
    <th>URL</th>
    <th>GitHub</th>
  </tr>
  <tr>
    <td>Docsify</td>
    <td><a href="https://github.com/docsifyjs/docsify/blob/develop/LICENSE" target="_blank" rel="noopener noreferrer">MIT License</a></td>
    <td>JavaScript</td>
    <td>VueJS</td>
    <td>Documentation</td>
    <td>VueJS/Markdown</td>
    <td>No</td>
    <td>No</td>
    <td>Good Support</td>
    <td>Easy</td>
    <td><a href="https://discord.gg/3NwKFyR" target="_blank" rel="noopener noreferrer">Docsify Discord</a></td>
    <td><a href="https://docsify.js.org/" target="_blank" rel="noopener noreferrer">Docsify Website</a></td>
    <td><a href="https://github.com/docsifyjs/docsify" target="_blank" rel="noopener noreferrer">Docsify GitHub</a></td>
  </tr>
  <tr>
    <td>Hugo</td>
    <td><a href="https://github.com/gohugoio/hugo/blob/master/LICENSE" target="_blank" rel="noopener noreferrer">Apache License 2.0</a></td>
    <td>Go</td>
    <td>None</td>
    <td>General</td>
    <td>Hugo Specific</td>
    <td>No</td>
    <td>No</td>
    <td>Good Support</td>
    <td>Medium</td>
    <td><a href="https://gitter.im/spf13/hugo" target="_blank" rel="noopener noreferrer">Hugo Gitter</a></td>
    <td><a href="https://gohugo.io/" target="_blank" rel="noopener noreferrer">Hugo Website</a></td>
    <td><a href="https://github.com/gohugoio/hugo" target="_blank" rel="noopener noreferrer">Hugo GitHub</a></td>
  </tr>
  <tr>
    <td>Docusaurus</td>
    <td><a href="https://github.com/facebook/docusaurus/blob/main/LICENSE" target="_blank" rel="noopener noreferrer">MIT License</a></td>
    <td>JavaScript</td>
    <td>React.js</td>
    <td>Documentation</td>
    <td>JSX/TSX (React Based)</td>
    <td>No</td>
    <td>No</td>
    <td>Very Good Support</td>
    <td>Easy</td>
    <td><a href="https://discordapp.com/invite/docusaurus" target="_blank" rel="noopener noreferrer">Docusaurus Discord</a></td>
    <td><a href="https://docusaurus.io/" target="_blank" rel="noopener noreferrer">Docusaurus Website</a></td>
    <td><a href="https://github.com/facebook/docusaurus" target="_blank" rel="noopener noreferrer">Docusaurus GitHub</a></td>
  </tr>
  <tr>
    <td>VuePress</td>
    <td><a href="https://github.com/vuejs/vuepress/blob/master/LICENSE" target="_blank" rel="noopener noreferrer">MIT License</a></td>
    <td>JavaScript</td>
    <td>Vue.js</td>
    <td>Documentation</td>
    <td>Vue.js/Markdown</td>
    <td>No</td>
    <td>No</td>
    <td>Good Support</td>
    <td>Easy</td>
    <td><a href="https://discord.com/invite/HBherRA" target="_blank" rel="noopener noreferrer">Vue.js Discord</a></td>
    <td><a href="https://vuepress.vuejs.org/" target="_blank" rel="noopener noreferrer">VuePress Website</a></td>
    <td><a href="https://github.com/vuejs/vuepress" target="_blank" rel="noopener noreferrer">VuePress GitHub</a></td>
  </tr>
  <tr>
    <td>Nuxt.js</td>
    <td><a href="https://github.com/nuxt/nuxt.js/blob/dev/LICENSE" target="_blank" rel="noopener noreferrer">MIT License</a></td>
    <td>JavaScript</td>
    <td>Vue.js</td>
    <td>Application</td>
    <td>Vue.js</td>
    <td>No</td>
    <td>No</td>
    <td>Good Support</td>
    <td>Easy</td>
    <td><a href="https://discord.com/invite/ps2h6QT" target="_blank" rel="noopener noreferrer">Nuxt.js Discord</a></td>
    <td><a href="https://nuxtjs.org/" target="_blank" rel="noopener noreferrer">Nuxt.js Website</a></td>
    <td><a href="https://github.com/nuxt/nuxt.js" target="_blank" rel="noopener noreferrer">Nuxt.js GitHub</a></td>
  </tr>
  <tr>
    <td>Next.js</td>
    <td><a href="https://github.com/vercel/next.js/blob/canary/license.md" target="_blank" rel="noopener noreferrer">MIT License</a></td>
    <td>JavaScript</td>
    <td>React.js</td>
    <td>Application</td>
    <td>JSX/TSX (React Based)</td>
    <td>Yes</td>
    <td>No</td>
    <td>Very Good Support</td>
    <td>Easy</td>
    <td><a href="https://nextjs.org/discord" target="_blank" rel="noopener noreferrer">Next.js Discord</a></td>
    <td><a href="https://nextjs.org/" target="_blank" rel="noopener noreferrer">Next.js Website</a></td>
    <td><a href="https://github.com/vercel/next.js" target="_blank" rel="noopener noreferrer">Next.js GitHub</a></td>
  </tr>
  <tr>
    <td>Gatsby.js</td>
    <td><a href="https://github.com/gatsbyjs/gatsby/blob/master/LICENSE" target="_blank" rel="noopener noreferrer">MIT License</a></td>
    <td>JavaScript</td>
    <td>React.js</td>
    <td>CMS</td>
    <td>JSX/TSX (React Based)</td>
    <td>Yes</td>
    <td>Yes</td>
    <td>Very Good Support</td>
    <td>Easy</td>
    <td><a href="https://gatsby.dev/discord" target="_blank" rel="noopener noreferrer">Gatsby.js Discord</a></td>
    <td><a href="https://www.gatsbyjs.com/" target="_blank" rel="noopener noreferrer">Gatsby.js Website</a></td>
    <td><a href="https://github.com/gatsbyjs/gatsby" target="_blank" rel="noopener noreferrer">Gatsby.js GitHub</a></td>
  </tr>
  <tr>
    <td>Jekyll</td>
    <td><a href="https://github.com/jekyll/jekyll/blob/master/LICENSE" target="_blank" rel="noopener noreferrer">MIT License</a></td>
    <td>Ruby</td>
    <td>None</td>
    <td>General</td>
    <td><a href="https://jekyllrb.com/docs/liquid/" target="_blank" rel="noopener noreferrer">Liquid</a></td>
    <td>No</td>
    <td>No</td>
    <td>Very Good Support</td>
    <td>Easy</td>
    <td><a href="https://jekyllrb.com/docs/community/" target="_blank" rel="noopener noreferrer">Jekyll Community</a></td>
    <td><a href="https://jekyllrb.com/" target="_blank" rel="noopener noreferrer">Jekyll Website</a></td>
    <td><a href="https://github.com/jekyll/jekyll" target="_blank" rel="noopener noreferrer">Jekyll GitHub</a></td>
  </tr>
</table>


## License:

[MIT License](LICENSE)