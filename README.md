# sttbtt.github.io

# Setting up custom domain with SSL.
1. Register Domain.
2. For using Cloudflare set DNS to: elma.ns.cloudflare.com and rommy.ns.cloudflare.com
3. Do not forward from domain host.
4. Setup SSL on Cloudflare.
    1. Setup A record with @ and IPs: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
    2. Setup CNAME with www and username.github.io.
5. Setup CNAME on github.

# Useful links
https://www.hover.com
https://www.cloudflare.com
https://medium.com/@hossainkhan/using-custom-domain-for-github-pages-86b303d3918a
https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/managing-a-custom-domain-for-your-github-pages-site
