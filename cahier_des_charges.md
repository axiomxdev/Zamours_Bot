---


---

<h1 id="cahier-des-charges-pour-zamours">Cahier des Charges pour Zamours</h1>
<h2 id="introduction">1. Introduction</h2>
<p>Ce document décrit les spécifications pour la création d’un bot Discord multifonctions en JavaScript. Le bot sera capable de gérer plusieurs tâches.</p>
<h2 id="objectifs">2. Objectifs</h2>
<ul>
<li>
<p>Créer un bot Discord en JavaScript.</p>
</li>
<li>
<p>Implémenter des fonctionnalités de modération.</p>
</li>
<li>
<p>Intégrer des mesures de protection.</p>
</li>
<li>
<p>Assurer une maintenance et une évolutivité faciles.</p>
</li>
</ul>
<h2 id="fonctionnalités">3. Fonctionnalités</h2>
<h3 id="modération">3.1 Modération</h3>
<h4 id="commandes-de-modération">3.1.1 Commandes de modération</h4>
<p>// pourquoi pas ajouté une commandes pour suivre les actions d’un user ( 2 commande, resumé les 20 dernière action du joueurs, créer un salon particulié pour suivre toutes les actions du user)</p>
<ul>
<li>
<p><strong>Bannir</strong> : <code>!ban [utilisateur] [raison]</code> Bannir un utilisateur du serveur pour une raison spécifique.</p>
</li>
<li>
<p><strong>Expulser</strong> : <code>!kick [utilisateur] [raison]</code> Expulser un utilisateur du serveur pour une raison spécifique.</p>
</li>
<li>
<p><strong>Muter</strong> : <code>!mute [utilisateur] [durée] [raison]</code> Empêcher un utilisateur de parler pendant une durée spécifique.</p>
</li>
<li>
<p><strong>Démuter</strong> : <code>!unmute [utilisateur]</code> Permettre à un utilisateur de parler à nouveau.</p>
</li>
<li>
<p><strong>Avertir</strong> : <code>!warn [utilisateur] [raison]</code> Envoyer un avertissement à un utilisateur pour une raison spécifique.</p>
</li>
<li>
<p><strong>Effacer des messages</strong> : <code>!clear [nombre de messages]</code> Effacer un nombre spécifique de messages dans un canal.</p>
</li>
<li>
<p><strong>Ajouter un rôle</strong> : <code>!addrole [utilisateur] [rôle]</code> Ajouter un rôle spécifique à un utilisateur.</p>
</li>
<li>
<p><strong>Retirer un rôle</strong> : <code>!removerole [utilisateur] [rôle]</code> Retirer un rôle spécifique d’un utilisateur.</p>
</li>
<li>
<p><strong>Rank up</strong> : <code>!rankup [utilisateur] [rang] [raison]</code> Promouvoir un utilisateur au rang supérieur (possibilité de spécifier un rang).</p>
</li>
<li>
<p><strong>Derank</strong> : <code>!derank [utilisateur] [raison]</code> Retirer les permissions de modération à un utilisateur.</p>
</li>
<li>
<p><strong>Verrouiller un canal</strong> : <code>!lock [canal]</code> Verrouiller un canal pour empêcher les utilisateurs d’envoyer des messages.</p>
</li>
<li>
<p><strong>Déverrouiller un canal</strong> : <code>!unlock [canal]</code> Déverrouiller un canal pour permettre aux utilisateurs d’envoyer des messages.</p>
</li>
<li>
<p><strong>Purge</strong> : <code>!purge [utilisateur] [raison]</code> Effacer tous les messages d’un utilisateur pour une raison spécifique.</p>
</li>
</ul>
<h3 id="sécurité">3.2 Sécurité</h3>
<h4 id="staff">3.2.1 Staff</h4>
<ul>
<li>
<p><strong>Anti-spam</strong> : Retirer les permissions en cas d’utilisation excessive de commandes de modération.</p>
</li>
<li>
<p><strong>Architecture des permissions/rôles</strong></p>
</li>
<li>
<p>rôle 1 permission (1) …</p>
</li>
</ul>
<h4 id="anti-sb">3.2.2 Anti-SB</h4>
<ul>
<li><strong>Bloquer les SB</strong> : Détection des selfbots et mise en quarantaine de l’utilisateur pour une durée déterminée.</li>
</ul>
<h2 id="technologies-utilisées">4. Technologies Utilisées</h2>
<ul>
<li>
<p><strong>Langage</strong> : JavaScript (Node.js v18.20.4 LTS)</p>
</li>
<li>
<p><strong>Bibliothèque</strong> : discord.js</p>
</li>
<li>
<p><strong>Base de données</strong> : sqlite</p>
</li>
</ul>
<h2 id="maintenance">5. Maintenance</h2>
<ul>
<li>
<p><strong>Documentation</strong> : Créer une documentation détaillée pour les développeurs.</p>
</li>
<li>
<p><strong>Support</strong> : Mettre en place un système de support pour les utilisateurs.</p>
</li>
</ul>

