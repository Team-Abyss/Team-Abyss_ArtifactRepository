Team-Abyss 成果物レポジトリ

レポジトリの追加

Maven

<pre>
  &lt;repositories&gt;
    &lt;repository&gt;
      &lt;id&gt;Abyss-repo&lt;/id&gt;
      &lt;name&gt;Team-Abyss Repository&lt;/name&gt;
      &lt;url&gt;https://raw.github.com/Team-Abyss/Team-Abyss_ArtifactRepository/master&lt;/url&gt;
    &lt;/repository&gt;
  &lt;/repositories&gt;
</pre>

Gradle
    maven {
        name = 'abyss-repo'
        url = 'https://raw.github.com/Team-Abyss/Team-Abyss_ArtifactRepository/master'
    }
