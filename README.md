# Shodanfy.py
Get ports,vulnerabilities,informations,banners,..etc for any IP with Shodan (no apikey! no rate limit!)

![main](https://i.imgur.com/TgTEYfL.png)


# Usage

``` **** USAGE **** 
# python3 shodanfy.py <ip> [OPTIONS] 
e.g:
    python3 shodanfy.py 111.111.111.111 
    python3 shodanfy.py 111.111.111.111 --getports
    python3 shodanfy.py 111.111.111.111 --getvuln
    python3 shodanfy.py 111.111.111.111 --getinfo
    python3 shodanfy.py 111.111.111.111 --getmoreinfo
    python3 shodanfy.py 111.111.111.111 --getbanner
    python3 shodanfy.py 111.111.111.111 --getports --getvuln
# support pipeline, --stdin option is required..
# echo "<ip>" or cat ips.txt | python3 shodanfy.py --stdin [OPTIONS]
e.g:
    echo "111.111.111.111"|python3 shodanfy.py --stdin 
    echo "111.111.111.111"|python3 shodanfy.py --stdin --getvuln 
    cat ips.txt|python3 shodanfy.py --stdin --getports
```
