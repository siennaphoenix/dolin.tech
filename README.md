# Blake Dolin

personal blog and homepage.

created by [blake@dolinit.com](mailto:blake@dolinit.com)

## Services

- [Admin Console](https://cockpit.dolinit.com)
- [Portainer](https://portainer.dolinit.com/)
- [Jellyfin](https://jellyfin.dolinit.com)
- [Jellyseerr](https://jellyseerr.dolinit.com)
- [RPC](https://rpc.dolinit.com/)
- [Foundry VTT](https://foundry.dolinit.com)

## Contact Me

- [Resume](/resume.html)
- [LinkedIn](https://www.linkedin.com/in/blakedolin)
- [Discord](https://discord.com/users/231844849433706506)
- [Signal](https://signal.me/#eu/zdjy_96_9ivRGo3XpHJSsNIP73o49SIrvQ7w-By81Jrm4FhqJCxBHLqaKMZSHeJm)
- [PGP Key](assets/Blake_Dolin_Pubkey.asc "Fingerprint: 0920CD4F5BA69E6AF25271786B8F7D1DEFD9D974")

## Blog

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
