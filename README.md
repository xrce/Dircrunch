# Dircrunch
Simple tool for Searching Directory from any Site and its Subdomain

## How to Use
```
php find.php <target> <list> <opt>
```

**Option List :**
- -s : Scan from target's Subdomains

**Example :**

```
php find.php google.com list.txt -s
```

## Dependencies
+ PHP
+ PHP-Curl

## Optional Dependencies
+ Custom Wordlists

## Similar Tools
+ [adfinder](https://github.com/N1ght420/adfinder) - Admin Login Finder

## External Links
+ [Subdoin](https://github.com/N1ght420/Subdoin) - Subdomain Grabber
+ [SubdoCheck](https://github.com/N1ght420/SubdoCheck) - Same as Subdoin, but written in Perl

## HTTP Response Explanation
+ **200 OK** - Request succeded, there is high probability that the file/directory is there
+ **302 Found** - Temporary redirected, maybe there is something on there, maybe not
+ **403 Forbidden** - You don't have access rights because it's unauthorized
+ **404 Not Found** - It's means the URL doesn't recognized
