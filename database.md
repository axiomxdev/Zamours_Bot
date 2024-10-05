---


---

<h1 id="visualision-de-la-db">Visualision de la db</h1>
<h2 id="permission">permission</h2>
<ul>
<li>0 membre .<br>
description : permission classique</li>
<li>1 <strong>staff junior</strong> :<br>
actions :
<ul>
<li>Signaler les mauvais comportement,</li>
</ul>
</li>
<li>2 <strong>staff classique</strong> :<br>
actions :
<ul>
<li>Supression de message unique,</li>
</ul>
</li>
<li>3 <strong>staff experimenté</strong> :<br>
actions :
<ul>
<li>mute vocal,</li>
<li>mute chat</li>
</ul>
</li>
<li>4 <strong>assisant chef staff</strong> :<br>
actions :
<ul>
<li>acces au casier des infractions</li>
</ul>
</li>
<li>5 <strong>chef staff junior</strong> :<br>
actions :
<ul>
<li>suppression en masse de message d’un membre,</li>
<li>accès au ticket staff,</li>
</ul>
</li>
<li>6 <strong>chef staff</strong> :<br>
actions :
<ul>
<li>gestion du casier des infractions,</li>
<li>peut rankup / derank</li>
</ul>
</li>
<li>7 <strong>responsable</strong> :<br>
actions :
<ul>
<li>kick,</li>
<li>ban,</li>
<li>lancé des évenement,o</li>
<li>accès au ticket gestion staff \ abus</li>
</ul>
</li>
<li>8 <strong>directeur</strong> :<br>
actions :
<ul>
<li>lock / delock les salon,</li>
<li>gestion total des membres</li>
</ul>
</li>
<li>9 <strong>propriétaire</strong> :<br>
actions :
<ul>
<li>gestion du prefix du bot</li>
</ul>
</li>
</ul>
<h2 id="membre">membre</h2>
<pre class=" language-json"><code class="prism  language-json"><span class="token punctuation">{</span>
	<span class="token string">"perms"</span><span class="token punctuation">:</span> <span class="token string">"permission du membre sur le bot, ex 6"</span>
<span class="token punctuation">}</span>
</code></pre>
<h2 id="guilds">Guilds</h2>
<ol>
<li>Config</li>
</ol>
<pre class=" language-json"><code class="prism  language-json"><span class="token punctuation">{</span>
	<span class="token string">'prefix'</span><span class="token punctuation">:</span><span class="token string">'par défaut : !'</span>
<span class="token punctuation">}</span>
</code></pre>

