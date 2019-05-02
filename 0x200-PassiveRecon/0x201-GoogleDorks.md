# Google Dorks / Google Hacking:
Google dorks are special searches you can perform on Google to find specific information. Say for example you want to find any PDF files related to a specific website, you can do that with special search terms. To accomplish this we can use search parameters such as "inurl" or "site".

Let's say we want to search for PDF files hosted on GitHub. We can use the "site" parameter to specify the site we want. We can specify the file type we want to search for with "filetype". The resulting query is:
```markdown
site:github.com filetype:pdf
```
If you type this into Google the response you get will be PDFs on GitHub. Play around with this and search for other file types. I've found a good amount of information using this technique such as employee names and roles.

You can also find passwords this way. We can use another keyword, "inurl", to get results with specified text in the URL. This is helpful when trying to find files that have specific information in them such as passwords because often the URL will be something like "https://www.example.com/2019EmployeePassword.xls". Before looking ahead, I want you to try to see if you can come up with a dork that will return documents with passwords in them.

The following will provide us with spread sheets (".xls" files) that have passwords in them:
```markdown
filetype:xls inurl:passwords
```
You can, and should, search for other file types such as .PDF and .DOC.

It's also possible to find default pages, login pages, configuration pages, and more. Information is exposed more than people think it is. Play around with Google dorks and see what you can find, you'll often be surprised.

## Final Notes:
You can do these same things on Bing. It's a good idea to use multiple search engines. Doing all of these searches can be tedious, thankfully there are tools that you can use and dorks that other people have made.

Hopefully you can start to see the potential Google dorks have.    
You can find Google dorks on Exploit-DB here:  
https://www.exploit-db.com/google-hacking-database.  
You can find more search terms here:  
https://www.searchenginejournal.com/google-search-operators-commands/215331/  