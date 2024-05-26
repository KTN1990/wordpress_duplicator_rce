# Duplicator < 1.3.0 - Unauthenticated RCE

[CVE-2018-25095](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-25095) The plugin does not properly escape values when its installer script replaces values in WordPress configuration files. If this installer script is left on the site after use, it could be use to run arbitrary code on the server.

For more exploits and exclusive ones contact me on telegram [@KtN1990](https://t.me/KtN1990).

## Usage

To run this exploit you need to have python 3 and websites list then execute

```bash
  python3 exploit.py -l list.txt -t 100
```

## Contact

- [@KtN1990](https://t.me/KtN1990)
- 
## More Exploits, Check Megatron!

![Logo](https://raw.githubusercontent.com/KTN1990/CVE-2022-0316_wordpress_multiple_themes_exploit/main/files/megatron.jpg)


- Provides an easy and efficient way to assess and exploit Wordpress security holes for mass purposes.
- 140+ Exploits, all types (RCE, LOOTS, AUTHBYPASS...).
- Customizable config.
- Monthly Free updates including more code opitmization, fixing bugs, adding more exploits plus 0days.
- Strong code base and custom threading and process model using a tasks management feature, getting reliable results is assured; no need to talk about speed since at KTN we use unconventional methods for concurrency.
- [Telegram Channel](https://t.me/megatron_ktn)



## Demo

[![IMAGE ALT TEXT HERE](https://i.ytimg.com/vi_webp/irrh91Iaz7c/mqdefault.webp)](https://www.youtube.com/watch?v=irrh91Iaz7c)

## License

[MIT](https://choosealicense.com/licenses/mit/)
