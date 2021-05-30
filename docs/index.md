## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/mountainrover/Cyber_Security/edit/main/docs/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

```markdown

//
Author : Deepak C Varghese
Tool   : recon -ng
OS     : Kali
Type   : Reconnaissance
URL    :https://tools.kali.org/information-gathering/recon-ng
Module :hackertarget
//


root@kali:~# 
root@kali:~# recon-ng
[*] Version check disabled.

    _/_/_/    _/_/_/_/    _/_/_/    _/_/_/    _/      _/            _/      _/    _/_/_/
   _/    _/  _/        _/        _/      _/  _/_/    _/            _/_/    _/  _/       
  _/_/_/    _/_/_/    _/        _/      _/  _/  _/  _/  _/_/_/_/  _/  _/  _/  _/  _/_/_/
 _/    _/  _/        _/        _/      _/  _/    _/_/            _/    _/_/  _/      _/ 
_/    _/  _/_/_/_/    _/_/_/    _/_/_/    _/      _/            _/      _/    _/_/_/    


                                          /\
                                         / \\ /\
    Sponsored by...               /\  /\/  \\V  \/\
                                 / \\/ // \\\\\ \\ \/\
                                // // BLACK HILLS \/ \\
                               www.blackhillsinfosec.com

                  ____   ____   ____   ____ _____ _  ____   ____  ____
                 |____] | ___/ |____| |       |   | |____  |____ |
                 |      |   \_ |    | |____   |   |  ____| |____ |____
                                   www.practisec.com

                      [recon-ng v5.0.0, Tim Tomes (@lanmaster53)]                       

[*] No modules enabled/installed.

[recon-ng][default] > help

Commands (type [help|?] <topic>):
---------------------------------
back            Exits the current context
dashboard       Displays a summary of activity
db              Interfaces with the workspace's database
exit            Exits the framework
help            Displays this menu
index           Creates a module index (dev only)
keys            Manages third party resource credentials
marketplace     Interfaces with the module marketplace
modules         Interfaces with installed modules
options         Manages the current context options
pdb             Starts a Python Debugger session (dev only)
script          Records and executes command scripts
shell           Executes shell commands
show            Shows various framework items
snapshots       Manages workspace snapshots
spool           Spools output to a file
workspaces      Manages workspaces

[recon-ng][default] > marketplace refresh
[*] Marketplace index refreshed.
[recon-ng][default] > options list

  Name        Current Value  Required  Description
  ----------  -------------  --------  -----------
  NAMESERVER  8.8.8.8        yes       default nameserver for the resolver mixin
  PROXY                      no        proxy server (address:port)
  THREADS     10             yes       number of threads (where applicable)
  TIMEOUT     10             yes       socket timeout (seconds)
  USER-AGENT  Recon-ng/v5    yes       user-agent string
  VERBOSITY   1              yes       verbosity level (0 = minimal, 1 = verbose, 2 = debug)

[recon-ng][default] > marketplace info all

  +------------------------------------------------------------------------------------+
  | path          | discovery/info_disclosure/cache_snoop                              |
  | name          | DNS Cache Snooper                                                  |
  | author        | thrapt (thrapt@gmail.com)                                          |
  | version       | 1.1                                                                |
  | last_updated  | 2020-10-13                                                         |
  | description   | Uses the DNS cache snooping technique to check for visited domains |
  | required_keys | []                                                                 |
  | dependencies  | []                                                                 |
  | files         | ['av_domains.lst']                                                 |
  | status        | not installed                                                      |
  +------------------------------------------------------------------------------------+


  +--------------------------------------------------------------------------------------------------------------+
  | path          | discovery/info_disclosure/interesting_files                                                  |
  | name          | Interesting File Finder                                                                      |
  | author        | Tim Tomes (@lanmaster53), thrapt (thrapt@gmail.com), Jay Turla (@shipcod3), and Mark Jeffery |
  | version       | 1.1                                                                                          |
  | last_updated  | 2020-01-13                                                                                   |
  | description   | Checks hosts for interesting files in predictable locations.                                 |
  | required_keys | []                                                                                           |
  | dependencies  | []                                                                                           |
  | files         | []                                                                                           |
  | status        | not installed                                                                                |
  +--------------------------------------------------------------------------------------------------------------+


  +----------------------------------------------------------------------------------------------------+
  | path          | exploitation/injection/command_injector                                            |
  | name          | Remote Command Injection Shell Interface                                           |
  | author        | Tim Tomes (@lanmaster53)                                                           |
  | version       | 1.0                                                                                |
  | last_updated  | 2019-06-24                                                                         |
  | description   | Provides a shell interface for remote command injection flaws in web applications. |
  | required_keys | []                                                                                 |
  | dependencies  | []                                                                                 |
  | files         | []                                                                                 |
  | status        | not installed                                                                      |
  +----------------------------------------------------------------------------------------------------+


  +-------------------------------------------------------------------------------------------------------+
  | path          | exploitation/injection/xpath_bruter                                                   |
  | name          | Xpath Injection Brute Forcer                                                          |
  | author        | Tim Tomes (@lanmaster53) & Justin Timko (@soloxdead)                                  |
  | version       | 1.2                                                                                   |
  | last_updated  | 2019-10-08                                                                            |
  | description   | Exploits XPath injection flaws to enumerate the contents of serverside XML documents. |
  | required_keys | []                                                                                    |
  | dependencies  | []                                                                                    |
  | files         | []                                                                                    |
  | status        | not installed                                                                         |
  +-------------------------------------------------------------------------------------------------------+


  +-----------------------------------------------------------------------+
  | path          | import/csv_file                                       |
  | name          | Advanced CSV File Importer                            |
  | author        | Ethan Robish (@EthanRobish)                           |
  | version       | 1.1                                                   |
  | last_updated  | 2019-08-09                                            |
  | description   | Imports values from a CSV file into a database table. |
  | required_keys | []                                                    |
  | dependencies  | []                                                    |
  | files         | []                                                    |
  | status        | not installed                                         |
  +-----------------------------------------------------------------------+


  +-----------------------------------------------------------------------------------+
  | path          | import/list                                                       |
  | name          | List File Importer                                                |
  | author        | Tim Tomes (@lanmaster53)                                          |
  | version       | 1.1                                                               |
  | last_updated  | 2019-06-24                                                        |
  | description   | Imports values from a list file into a database table and column. |
  | required_keys | []                                                                |
  | dependencies  | []                                                                |
  | files         | []                                                                |
  | status        | not installed                                                     |
  +-----------------------------------------------------------------------------------+


  +------------------------------------------------------------------------------------------------+
  | path          | import/masscan                                                                 |
  | name          | Masscan XML Output Importer                                                    |
  | author        | Ryan Hays (@_ryanhays)                                                         |
  | version       | 1.0                                                                            |
  | last_updated  | 2020-04-07                                                                     |
  | description   | Imports hosts and ports into the respective databases from Masscan XML output. |
  | required_keys | []                                                                             |
  | dependencies  | []                                                                             |
  | files         | []                                                                             |
  | status        | not installed                                                                  |
  +------------------------------------------------------------------------------------------------+


  +---------------------------------------------------------------------------------------------+
  | path          | import/nmap                                                                 |
  | name          | Nmap XML Output Importer                                                    |
  | author        | Ryan Hays (@_ryanhays)                                                      |
  | version       | 1.1                                                                         |
  | last_updated  | 2020-10-06                                                                  |
  | description   | Imports hosts and ports into the respective databases from Nmap XML output. |
  | required_keys | []                                                                          |
  | dependencies  | []                                                                          |
  | files         | []                                                                          |
  | status        | not installed                                                               |
  +---------------------------------------------------------------------------------------------+


  +-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/companies-contacts/bing_linkedin_cache                                                                                                                                                                                                                                                                                                                                                                            |
  | name          | Bing Cache Linkedin Profile and Contact Harvester                                                                                                                                                                                                                                                                                                                                                                       |
  | author        | Joe Black (@MyChickenNinja), @fullmetalcache, and Brian King                                                                                                                                                                                                                                                                                                                                                            |
  | version       | 1.0                                                                                                                                                                                                                                                                                                                                                                                                                     |
  | last_updated  | 2019-06-24                                                                                                                                                                                                                                                                                                                                                                                                              |
  | description   | Harvests profiles from LinkedIn by querying the Bing API cache for LinkedIn pages related to the given companies, and adds them to the 'profiles' table. The module will then parse the resulting information to extract the user's full name and job title (title parsing recently improved). The user's full name and title are then added to the 'contacts' table. This module does not access LinkedIn at any time. |
  | required_keys | ['bing_api']                                                                                                                                                                                                                                                                                                                                                                                                            |
  | dependencies  | []                                                                                                                                                                                                                                                                                                                                                                                                                      |
  | files         | []                                                                                                                                                                                                                                                                                                                                                                                                                      |
  | status        | not installed                                                                                                                                                                                                                                                                                                                                                                                                           |
  +-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+


  +-----------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/companies-contacts/censys_email_address                                                                     |
  | name          | Censys emails by company                                                                                          |
  | author        | Censys Team                                                                                                       |
  | version       | 2.0                                                                                                               |
  | last_updated  | 2021-05-11                                                                                                        |
  | description   | Retrieves email addresses from the TLS certificates for a company. Updates the 'contacts' table with the results. |
  | required_keys | ['censysio_id', 'censysio_secret']                                                                                |
  | dependencies  | ['censys>=2.0.0']                                                                                                 |
  | files         | []                                                                                                                |
  | status        | not installed                                                                                                     |
  +-----------------------------------------------------------------------------------------------------------------------------------+


  +--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/companies-contacts/pen                                                                                                                                                                 |
  | name          | IANA Private Enterprise Number Contact Getter                                                                                                                                                |
  | author        | Jonathan M. Wilbur <jonathan@wilbur.space>                                                                                                                                                   |
  | version       | 1.1                                                                                                                                                                                          |
  | last_updated  | 2019-10-15                                                                                                                                                                                   |
  | description   | Given a company name, gathers the registered IANA Private Enterprise Number (PEN) contact from the PEN registry and adds the contacts's full name and email address to the 'contacts' table. |
  | required_keys | []                                                                                                                                                                                           |
  | dependencies  | []                                                                                                                                                                                           |
  | files         | []                                                                                                                                                                                           |
  | status        | not installed                                                                                                                                                                                |
  +--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+


  +----------------------------------------------------------------------------------------------------+
  | path          | recon/companies-domains/censys_subdomains                                          |
  | name          | Censys subdomains by company                                                       |
  | author        | Censys Team                                                                        |
  | version       | 2.0                                                                                |
  | last_updated  | 2021-05-10                                                                         |
  | description   | Retrieves subdomains for a company. Updates the 'domains' tables with the results. |
  | required_keys | ['censysio_id', 'censysio_secret']                                                 |
  | dependencies  | ['censys>=2.0.0']                                                                  |
  | files         | []                                                                                 |
  | status        | not installed                                                                      |
  +----------------------------------------------------------------------------------------------------+


  +--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/companies-domains/pen                                                                                                                                                            |
  | name          | IANA Private Enterprise Number Domain Getter                                                                                                                                           |
  | author        | Jonathan M. Wilbur <jonathan@wilbur.space>                                                                                                                                             |
  | version       | 1.1                                                                                                                                                                                    |
  | last_updated  | 2019-10-15                                                                                                                                                                             |
  | description   | Given a company name, gathers a domain from the email address of the registered IANA Private Enterprise Number (PEN) contact from the PEN registry and adds it to the 'domains' table. |
  | required_keys | []                                                                                                                                                                                     |
  | dependencies  | []                                                                                                                                                                                     |
  | files         | []                                                                                                                                                                                     |
  | status        | not installed                                                                                                                                                                          |
  +--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+


  +-----------------------------------------------------------------------------------------------------------------+
  | path          | recon/companies-domains/viewdns_reverse_whois                                                   |
  | name          | Viewdns Reverse Whois Domain Harvester                                                          |
  | author        | Gaetan Ferry (@_mabote_) from @synacktiv                                                        |
  | version       | 1.0                                                                                             |
  | last_updated  | 2019-08-08                                                                                      |
  | description   | Harvests domain names belonging to a company by using the viewdns.info free reverse whois tool. |
  | required_keys | []                                                                                              |
  | dependencies  | []                                                                                              |
  | files         | []                                                                                              |
  | status        | not installed                                                                                   |
  +-----------------------------------------------------------------------------------------------------------------+


  +--------------------------------------------------------------------------------+
  | path          | recon/companies-domains/whoxy_dns                              |
  | name          | Whoxy Company DNS Lookup                                       |
  | author        | Ryan Hays (@_ryanhays)                                         |
  | version       | 1.1                                                            |
  | last_updated  | 2020-06-17                                                     |
  | description   | Uses the Whoxy API to query DNS records belonging to a company |
  | required_keys | ['whoxy_api']                                                  |
  | dependencies  | []                                                             |
  | files         | []                                                             |
  | status        | not installed                                                  |
  +--------------------------------------------------------------------------------+


  +-------------------------------------------------------------------------------------------------------------------+
  | path          | recon/companies-hosts/censys_org                                                                  |
  | name          | Censys services by company                                                                        |
  | author        | Censys Team                                                                                       |
  | version       | 2.0                                                                                               |
  | last_updated  | 2021-05-11                                                                                        |
  | description   | Retrieves hosts for a company's ASN. Updates the 'hosts' and the 'ports' tables with the results. |
  | required_keys | ['censysio_id', 'censysio_secret']                                                                |
  | dependencies  | ['censys>=2.0.0']                                                                                 |
  | files         | []                                                                                                |
  | status        | not installed                                                                                     |
  +-------------------------------------------------------------------------------------------------------------------+


  +-----------------------------------------------------------------------------------------------------------------------+
  | path          | recon/companies-hosts/censys_tls_subjects                                                             |
  | name          | Censys domains by company                                                                             |
  | author        | Censys Team                                                                                           |
  | version       | 2.0                                                                                                   |
  | last_updated  | 2021-05-11                                                                                            |
  | description   | Retrieves the TLS certificates for a domain. Updates the 'hosts' and 'ports' tables with the results. |
  | required_keys | ['censysio_id', 'censysio_secret']                                                                    |
  | dependencies  | ['censys>=2.0.0']                                                                                     |
  | files         | []                                                                                                    |
  | status        | not installed                                                                                         |
  +-----------------------------------------------------------------------------------------------------------------------+


  +----------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/companies-multi/github_miner                                                                                                                         |
  | name          | Github Resource Miner                                                                                                                                      |
  | author        | Tim Tomes (@lanmaster53)                                                                                                                                   |
  | version       | 1.1                                                                                                                                                        |
  | last_updated  | 2020-05-15                                                                                                                                                 |
  | description   | Uses the Github API to enumerate repositories and member profiles associated with a company search string. Updates the respective tables with the results. |
  | required_keys | ['github_api']                                                                                                                                             |
  | dependencies  | []                                                                                                                                                         |
  | files         | []                                                                                                                                                         |
  | status        | not installed                                                                                                                                              |
  +----------------------------------------------------------------------------------------------------------------------------------------------------------------------------+


  +---------------------------------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/companies-multi/shodan_org                                                                                                                    |
  | name          | Shodan IP Enumerator                                                                                                                                |
  | author        | Austin Tipton (@hiEntropy404) & Ryan Hays (@_ryanhays)                                                                                              |
  | version       | 1.1                                                                                                                                                 |
  | last_updated  | 2020-07-01                                                                                                                                          |
  | description   | Harvests host and port information from the Shodan API by using the 'org' search operator. Updates the 'hosts' and 'ports' tables with the results. |
  | required_keys | ['shodan_api']                                                                                                                                      |
  | dependencies  | ['shodan']                                                                                                                                          |
  | files         | []                                                                                                                                                  |
  | status        | not installed                                                                                                                                       |
  +---------------------------------------------------------------------------------------------------------------------------------------------------------------------+


  +---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/companies-multi/whois_miner                                                                                                                                                 |
  | name          | Whois Data Miner                                                                                                                                                                  |
  | author        | Tim Tomes (@lanmaster53)                                                                                                                                                          |
  | version       | 1.1                                                                                                                                                                               |
  | last_updated  | 2019-10-15                                                                                                                                                                        |
  | description   | Uses the ARIN Whois RWS to harvest companies, locations, netblocks, and contacts associated with the given company search string. Updates the respective tables with the results. |
  | required_keys | []                                                                                                                                                                                |
  | dependencies  | []                                                                                                                                                                                |
  | files         | []                                                                                                                                                                                |
  | status        | not installed                                                                                                                                                                     |
  +---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+


  +---------------------------------------------------------------+
  | path          | recon/contacts-contacts/abc                   |
  | name          | Advance Background Check Lookup               |
  | author        | Cam Barts (@cam-barts)                        |
  | version       | 1.0                                           |
  | last_updated  | 2019-10-11                                    |
  | description   | Checks names at advancedbackgroundchecks.com. |
  | required_keys | []                                            |
  | dependencies  | ['beautifulsoup4']                            |
  | files         | []                                            |
  | status        | not installed                                 |
  +---------------------------------------------------------------+


  +-----------------------------------------------------------------------+
  | path          | recon/contacts-contacts/mailtester                    |
  | name          | MailTester Email Validator                            |
  | author        | Tim Tomes (@lanmaster53)                              |
  | version       | 1.0                                                   |
  | last_updated  | 2019-06-24                                            |
  | description   | Leverages MailTester.com to validate email addresses. |
  | required_keys | []                                                    |
  | dependencies  | []                                                    |
  | files         | []                                                    |
  | status        | not installed                                         |
  +-----------------------------------------------------------------------+


  +----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/contacts-contacts/mangle                                                                                                                                                           |
  | name          | Contact Name Mangler                                                                                                                                                                     |
  | author        | Tim Tomes (@lanmaster53)                                                                                                                                                                 |
  | version       | 1.0                                                                                                                                                                                      |
  | last_updated  | 2019-06-24                                                                                                                                                                               |
  | description   | Applies a mangle pattern to all of the contacts stored in the database, creating email addresses or usernames for each harvested contact. Updates the 'contacts' table with the results. |
  | required_keys | []                                                                                                                                                                                       |
  | dependencies  | []                                                                                                                                                                                       |
  | files         | []                                                                                                                                                                                       |
  | status        | not installed                                                                                                                                                                            |
  +----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+


  +-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/contacts-contacts/unmangle                                                                                                                                              |
  | name          | Contact Name Unmangler                                                                                                                                                        |
  | author        | Ethan Robish (@EthanRobish)                                                                                                                                                   |
  | version       | 1.1                                                                                                                                                                           |
  | last_updated  | 2019-10-27                                                                                                                                                                    |
  | description   | Applies a regex or unmangle pattern to all of the contacts stored in the database, pulling out the individual name components. Updates the 'contacts' table with the results. |
  | required_keys | []                                                                                                                                                                            |
  | dependencies  | []                                                                                                                                                                            |
  | files         | []                                                                                                                                                                            |
  | status        | not installed                                                                                                                                                                 |
  +-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+


  +---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/contacts-credentials/hibp_breach                                                                                                                                      |
  | name          | Have I been pwned? Breach Search                                                                                                                                            |
  | author        | Tim Tomes (@lanmaster53), Tyler Halfpop (@tylerhalfpop) and Geoff Pamerleau (@_geoff_p_)                                                                                    |
  | version       | 1.2                                                                                                                                                                         |
  | last_updated  | 2019-09-10                                                                                                                                                                  |
  | description   | Leverages the haveibeenpwned.com API to determine if email addresses are associated with breached credentials. Adds compromised email addresses to the 'credentials' table. |
  | required_keys | ['hibp_api']                                                                                                                                                                |
  | dependencies  | []                                                                                                                                                                          |
  | files         | []                                                                                                                                                                          |
  | status        | not installed                                                                                                                                                               |
  +---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+


  +-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/contacts-credentials/hibp_paste                                                                                                                                         |
  | name          | Have I been pwned? Paste Search                                                                                                                                               |
  | author        | Tim Tomes (@lanmaster53) and Geoff Pamerleau (@_geoff_p_)                                                                                                                     |
  | version       | 1.1                                                                                                                                                                           |
  | last_updated  | 2019-09-10                                                                                                                                                                    |
  | description   | Leverages the haveibeenpwned.com API to determine if email addresses have been published to various paste sites. Adds compromised email addresses to the 'credentials' table. |
  | required_keys | ['hibp_api']                                                                                                                                                                  |
  | dependencies  | []                                                                                                                                                                            |
  | files         | []                                                                                                                                                                            |
  | status        | not installed                                                                                                                                                                 |
  +-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+


  +---------------------------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/contacts-credentials/scylla                                                                                                             |
  | name          | Scylla Targetted Credential Harvester                                                                                                         |
  | author        | Tim Tomes (@lanmaster53)                                                                                                                      |
  | version       | 1.3                                                                                                                                           |
  | last_updated  | 2020-09-14                                                                                                                                    |
  | description   | Harvests credentials from the scylla.sh API using email addresses as input. Updates the 'credentials' and 'contacts' tables with the results. |
  | required_keys | []                                                                                                                                            |
  | dependencies  | []                                                                                                                                            |
  | files         | []                                                                                                                                            |
  | status        | not installed                                                                                                                                 |
  +---------------------------------------------------------------------------------------------------------------------------------------------------------------+


  +-------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/contacts-domains/migrate_contacts                                                                 |
  | name          | Contacts to Domains Data Migrator                                                                       |
  | author        | Tim Tomes (@lanmaster53)                                                                                |
  | version       | 1.1                                                                                                     |
  | last_updated  | 2020-05-17                                                                                              |
  | description   | Adds a new domain for all the hostnames associated with email addresses stored in the 'contacts' table. |
  | required_keys | []                                                                                                      |
  | dependencies  | []                                                                                                      |
  | files         | ['suffixes.txt']                                                                                        |
  | status        | not installed                                                                                           |
  +-------------------------------------------------------------------------------------------------------------------------+


  +---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/contacts-profiles/fullcontact                                                                                                                                   |
  | name          | FullContact Contact Enumerator                                                                                                                                        |
  | author        | Tim Tomes (@lanmaster53) and Cam Barts (@cam-barts)                                                                                                                   |
  | version       | 1.1                                                                                                                                                                   |
  | last_updated  | 2019-07-24                                                                                                                                                            |
  | description   | Harvests contact information and profiles from the fullcontact.com API using email addresses as input. Updates the 'contacts' and 'profiles' tables with the results. |
  | required_keys | ['fullcontact_api']                                                                                                                                                   |
  | dependencies  | []                                                                                                                                                                    |
  | files         | []                                                                                                                                                                    |
  | status        | not installed                                                                                                                                                         |
  +---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+


  +----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/credentials-credentials/adobe                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
  | name          | Adobe Hash Cracker                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
  | author        | Ethan Robish (@EthanRobish) and Tim Tomes (@lanmaster53)                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
  | version       | 1.0                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
  | last_updated  | 2019-06-24                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
  | description   | Decrypts hashes leaked from the 2013 Adobe breach. First, the module cross references the leak ID to identify Adobe hashes in the 'password' column of the 'creds' table, moves the Adobe hashes to the 'hash' column, and changes the 'type' to 'Adobe'. Second, the module attempts to crack the hashes by comparing the ciphertext's decoded cipher blocks to a local block lookup table (BLOCK_DB) of known cipher block values. Finally, the module updates the 'creds' table with the results based on the level of success. |
  | required_keys | []                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
  | dependencies  | []                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
  | files         | ['adobe_blocks.json']                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
  | status        | not installed                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
  +----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+


  +-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/credentials-credentials/bozocrack                                                                                                                                                                                               |
  | name          | PyBozoCrack Hash Lookup                                                                                                                                                                                                               |
  | author        | Tim Tomes (@lanmaster53)                                                                                                                                                                                                              |
  | version       | 1.0                                                                                                                                                                                                                                   |
  | last_updated  | 2019-06-24                                                                                                                                                                                                                            |
  | description   | Searches Google for the value of a hash and tests for a match by hashing every word in the resulting page using all hashing algorithms supported by the 'hashlib' library. Updates the 'credentials' table with the positive results. |
  | required_keys | []                                                                                                                                                                                                                                    |
  | dependencies  | []                                                                                                                                                                                                                                    |
  | files         | []                                                                                                                                                                                                                                    |
  | status        | not installed                                                                                                                                                                                                                         |
  +-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+


  +--------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/credentials-credentials/hashes_org                                                                             |
  | name          | Hashes.org Hash Lookup                                                                                               |
  | author        | Tim Tomes (@lanmaster53) and Mike Lisi (@MikeCodesThings)                                                            |
  | version       | 1.0                                                                                                                  |
  | last_updated  | 2019-06-24                                                                                                           |
  | description   | Uses the Hashes.org API to perform a reverse hash lookup. Updates the 'credentials' table with the positive results. |
  | required_keys | ['hashes_api']                                                                                                       |
  | dependencies  | []                                                                                                                   |
  | files         | []                                                                                                                   |
  | status        | not installed                                                                                                        |
  +--------------------------------------------------------------------------------------------------------------------------------------+


  +-------------------------------------------------------------------------------------------------------------+
  | path          | recon/domains-companies/censys_companies                                                    |
  | name          | Censys companies by domain                                                                  |
  | author        | Censys Team                                                                                 |
  | version       | 2.0                                                                                         |
  | last_updated  | 2021-05-10                                                                                  |
  | description   | Retrieves the TLS certificates for a domain. Updates the 'companies' table with the results |
  | required_keys | ['censysio_id', 'censysio_secret']                                                          |
  | dependencies  | ['censys>=2.0.0']                                                                           |
  | files         | []                                                                                          |
  | status        | not installed                                                                               |
  +-------------------------------------------------------------------------------------------------------------+


  +----------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/domains-companies/pen                                                                                                  |
  | name          | IANA Private Enterprise Number Company-by-Domain Lookup                                                                      |
  | author        | Jonathan M. Wilbur <jonathan@wilbur.space>                                                                                   |
  | version       | 1.1                                                                                                                          |
  | last_updated  | 2019-10-15                                                                                                                   |
  | description   | Given a domain, finds companies in the IANA Private Enterprise Number (PEN) registry and adds them to the 'companies' table. |
  | required_keys | []                                                                                                                           |
  | dependencies  | []                                                                                                                           |
  | files         | []                                                                                                                           |
  | status        | not installed                                                                                                                |
  +----------------------------------------------------------------------------------------------------------------------------------------------+


  +----------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/domains-companies/whoxy_whois                                                                        |
  | name          | Whoxy Whois Lookup                                                                                         |
  | author        | Ryan Hays (@_ryanhays)                                                                                     |
  | version       | 1.1                                                                                                        |
  | last_updated  | 2020-06-24                                                                                                 |
  | description   | Uses the Whoxy API to query whois information for a domain and updates the companies and contacts tables.  |
  | required_keys | ['whoxy_api']                                                                                              |
  | dependencies  | []                                                                                                         |
  | files         | []                                                                                                         |
  | status        | not installed                                                                                              |
  +----------------------------------------------------------------------------------------------------------------------------+


  +---------------------------------------------------------------------------+
  | path          | recon/domains-contacts/hunter_io                          |
  | name          | Hunter.io Email Address Harvester                         |
  | author        | Super Choque (@aplneto)                                   |
  | version       | 1.3                                                       |
  | last_updated  | 2020-04-14                                                |
  | description   | Uses Hunter.io to find email addresses for given domains. |
  | required_keys | ['hunter_io']                                             |
  | dependencies  | []                                                        |
  | files         | []                                                        |
  | status        | not installed                                             |
  +---------------------------------------------------------------------------+


  +----------------------------------------------------------------------------------------------------------------------+
  | path          | recon/domains-contacts/metacrawler                                                                   |
  | name          | Meta Data Extractor                                                                                  |
  | author        | Tim Tomes (@lanmaster53)                                                                             |
  | version       | 1.1                                                                                                  |
  | last_updated  | 2019-06-24                                                                                           |
  | description   | Searches for files associated with the provided domain(s) and extracts any contact related metadata. |
  | required_keys | []                                                                                                   |
  | dependencies  | ['olefile', 'pypdf3', 'lxml']                                                                        |
  | files         | []                                                                                                   |
  | status        | not installed                                                                                        |
  +----------------------------------------------------------------------------------------------------------------------+


  +--------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/domains-contacts/pen                                                                                                 |
  | name          | IANA Private Enterprise Number Contact-by-Domain Lookup                                                                    |
  | author        | Jonathan M. Wilbur <jonathan@wilbur.space>                                                                                 |
  | version       | 1.1                                                                                                                        |
  | last_updated  | 2019-10-15                                                                                                                 |
  | description   | Given a domain, finds contacts in the IANA Private Enterprise Number (PEN) registry and adds them to the 'contacts' table. |
  | required_keys | []                                                                                                                         |
  | dependencies  | []                                                                                                                         |
  | files         | []                                                                                                                         |
  | status        | not installed                                                                                                              |
  +--------------------------------------------------------------------------------------------------------------------------------------------+


  +------------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/domains-contacts/pgp_search                                                                                              |
  | name          | PGP Key Owner Lookup                                                                                                           |
  | author        | Robert Frost (@frosty_1313, frosty[at]unluckyfrosty.net) and Cam Barts (@cam-barts)                                            |
  | version       | 1.4                                                                                                                            |
  | last_updated  | 2019-10-16                                                                                                                     |
  | description   | Searches the MIT public PGP key server for email addresses of the given domain. Updates the 'contacts' table with the results. |
  | required_keys | []                                                                                                                             |
  | dependencies  | []                                                                                                                             |
  | files         | []                                                                                                                             |
  | status        | not installed                                                                                                                  |
  +------------------------------------------------------------------------------------------------------------------------------------------------+


  +-----------------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/domains-contacts/whois_pocs                                                                                                   |
  | name          | Whois POC Harvester                                                                                                                 |
  | author        | Tim Tomes (@lanmaster53)                                                                                                            |
  | version       | 1.0                                                                                                                                 |
  | last_updated  | 2019-06-24                                                                                                                          |
  | description   | Uses the ARIN Whois RWS to harvest POC data from whois queries for the given domain. Updates the 'contacts' table with the results. |
  | required_keys | []                                                                                                                                  |
  | dependencies  | []                                                                                                                                  |
  | files         | []                                                                                                                                  |
  | status        | not installed                                                                                                                       |
  +-----------------------------------------------------------------------------------------------------------------------------------------------------+


  +---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/domains-contacts/wikileaker                                                                                                                                                                                                                                                                                                 |
  | name          | WikiLeaker                                                                                                                                                                                                                                                                                                                        |
  | author        | Joe Gray (@C_3PJoe)                                                                                                                                                                                                                                                                                                               |
  | version       | 1.0                                                                                                                                                                                                                                                                                                                               |
  | last_updated  | 2020-04-08                                                                                                                                                                                                                                                                                                                        |
  | description   | A WikiLeaks scraper inspired by the Datasploit module previously written in Python2. It searches Wikileaks for leaks containing the subject domain. If anything is found, this module will seek to parse out the URL, Sender Email, Date, Leak, and Subject of the email. This will update the 'Contacts' table with the results. |
  | required_keys | []                                                                                                                                                                                                                                                                                                                                |
  | dependencies  | []                                                                                                                                                                                                                                                                                                                                |
  | files         | []                                                                                                                                                                                                                                                                                                                                |
  | status        | not installed                                                                                                                                                                                                                                                                                                                     |
  +---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+


  +--------------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/domains-credentials/pwnedlist/account_creds                                                                                |
  | name          | PwnedList - Account Credentials Fetcher                                                                                          |
  | author        | Tim Tomes (@lanmaster53)                                                                                                         |
  | version       | 1.0                                                                                                                              |
  | last_updated  | 2019-06-24                                                                                                                       |
  | description   | Queries the PwnedList API for credentials associated with the given usernames. Updates the 'credentials' table with the results. |
  | required_keys | ['pwnedlist_api', 'pwnedlist_secret', 'pwnedlist_iv']                                                                            |
  | dependencies  | ['pyaes']                                                                                                                        |
  | files         | []                                                                                                                               |
  | status        | not installed                                                                                                                    |
  +--------------------------------------------------------------------------------------------------------------------------------------------------+


  +-------------------------------------------------------------------------+
  | path          | recon/domains-credentials/pwnedlist/api_usage           |
  | name          | PwnedList - API Usage Statistics Fetcher                |
  | author        | Tim Tomes (@lanmaster53)                                |
  | version       | 1.0                                                     |
  | last_updated  | 2019-06-24                                              |
  | description   | Queries the PwnedList API for account usage statistics. |
  | required_keys | ['pwnedlist_api', 'pwnedlist_secret']                   |
  | dependencies  | []                                                      |
  | files         | []                                                      |
  | status        | not installed                                           |
  +-------------------------------------------------------------------------+


  +------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/domains-credentials/pwnedlist/domain_creds                                                                   |
  | name          | PwnedList - Pwned Domain Credentials Fetcher                                                                       |
  | author        | Tim Tomes (@lanmaster53)                                                                                           |
  | version       | 1.0                                                                                                                |
  | last_updated  | 2019-06-24                                                                                                         |
  | description   | Queries the PwnedList API to fetch all credentials for a domain. Updates the 'credentials' table with the results. |
  | required_keys | ['pwnedlist_api', 'pwnedlist_secret', 'pwnedlist_iv']                                                              |
  | dependencies  | ['pycryptodome']                                                                                                   |
  | files         | []                                                                                                                 |
  | status        | not installed                                                                                                      |
  +------------------------------------------------------------------------------------------------------------------------------------+


  +-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/domains-credentials/pwnedlist/domain_ispwned                                                                                                                                                    |
  | name          | PwnedList - Pwned Domain Statistics Fetcher                                                                                                                                                           |
  | author        | Tim Tomes (@lanmaster53)                                                                                                                                                                              |
  | version       | 1.0                                                                                                                                                                                                   |
  | last_updated  | 2019-06-24                                                                                                                                                                                            |
  | description   | Queries the PwnedList API for a domain to determine if any associated credentials have been compromised. This module does NOT return any credentials, only a total number of compromised credentials. |
  | required_keys | ['pwnedlist_api', 'pwnedlist_secret']                                                                                                                                                                 |
  | dependencies  | []                                                                                                                                                                                                    |
  | files         | []                                                                                                                                                                                                    |
  | status        | not installed                                                                                                                                                                                         |
  +-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+


  +---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/domains-credentials/pwnedlist/leak_lookup                                                                                                                                         |
  | name          | PwnedList - Leak Details Fetcher                                                                                                                                                        |
  | author        | Tim Tomes (@lanmaster53)                                                                                                                                                                |
  | version       | 1.0                                                                                                                                                                                     |
  | last_updated  | 2019-06-24                                                                                                                                                                              |
  | description   | Queries the local database for information associated with a leak ID. The 'leaks_dump' module must be used to populate the local database before this module will execute successfully. |
  | required_keys | []                                                                                                                                                                                      |
  | dependencies  | []                                                                                                                                                                                      |
  | files         | []                                                                                                                                                                                      |
  | status        | not installed                                                                                                                                                                           |
  +---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+


  +----------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/domains-credentials/pwnedlist/leaks_dump                                                                         |
  | name          | PwnedList - Leak Details Retriever                                                                                     |
  | author        | Tim Tomes (@lanmaster53)                                                                                               |
  | version       | 1.0                                                                                                                    |
  | last_updated  | 2019-06-24                                                                                                             |
  | description   | Queries the PwnedList API for information associated with all known leaks. Updates the 'leaks' table with the results. |
  | required_keys | ['pwnedlist_api', 'pwnedlist_secret']                                                                                  |
  | dependencies  | []                                                                                                                     |
  | files         | []                                                                                                                     |
  | status        | not installed                                                                                                          |
  +----------------------------------------------------------------------------------------------------------------------------------------+


  +-------------------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/domains-credentials/scylla                                                                                                      |
  | name          | Scylla Bulk Credential Harvester                                                                                                      |
  | author        | Tim Tomes (@lanmaster53)                                                                                                              |
  | version       | 1.3                                                                                                                                   |
  | last_updated  | 2020-09-25                                                                                                                            |
  | description   | Harvests credentials from the scylla.sh API using domains as input. Updates the 'credentials' and 'contacts' tables with the results. |
  | required_keys | []                                                                                                                                    |
  | dependencies  | []                                                                                                                                    |
  | files         | []                                                                                                                                    |
  | status        | not installed                                                                                                                         |
  +-------------------------------------------------------------------------------------------------------------------------------------------------------+


  +-----------------------------------------------------------------------------------------------------+
  | path          | recon/domains-domains/brute_suffix                                                  |
  | name          | DNS Public Suffix Brute Forcer                                                      |
  | author        | Marcus Watson (@BranMacMuffin)                                                      |
  | version       | 1.1                                                                                 |
  | last_updated  | 2020-05-17                                                                          |
  | description   | Brute forces TLDs and SLDs using DNS. Updates the 'domains' table with the results. |
  | required_keys | []                                                                                  |
  | dependencies  | []                                                                                  |
  | files         | ['suffixes.txt']                                                                    |
  | status        | not installed                                                                       |
  +-----------------------------------------------------------------------------------------------------+


  +-----------------------------------------------------------------+
  | path          | recon/domains-hosts/binaryedge                  |
  | name          | BinaryEdge.io DNS lookup                        |
  | author        | Ryan Hays                                       |
  | version       | 1.2                                             |
  | last_updated  | 2020-06-18                                      |
  | description   | Uses the BinaryEdge API to discover subdomains. |
  | required_keys | ['binaryedge_api']                              |
  | dependencies  | []                                              |
  | files         | []                                              |
  | status        | not installed                                   |
  +-----------------------------------------------------------------+


  +---------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/domains-hosts/bing_domain_api                                                                                         |
  | name          | Bing API Hostname Enumerator                                                                                                |
  | author        | Marcus Watson (@BranMacMuffin)                                                                                              |
  | version       | 1.0                                                                                                                         |
  | last_updated  | 2019-06-24                                                                                                                  |
  | description   | Leverages the Bing API and "domain:" advanced search operator to harvest hosts. Updates the 'hosts' table with the results. |
  | required_keys | ['bing_api']                                                                                                                |
  | dependencies  | []                                                                                                                          |
  | files         | []                                                                                                                          |
  | status        | not installed                                                                                                               |
  +---------------------------------------------------------------------------------------------------------------------------------------------+


  +-------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/domains-hosts/bing_domain_web                                                                           |
  | name          | Bing Hostname Enumerator                                                                                      |
  | author        | Tim Tomes (@lanmaster53)                                                                                      |
  | version       | 1.1                                                                                                           |
  | last_updated  | 2019-07-04                                                                                                    |
  | description   | Harvests hosts from Bing.com by using the 'site' search operator. Updates the 'hosts' table with the results. |
  | required_keys | []                                                                                                            |
  | dependencies  | []                                                                                                            |
  | files         | []                                                                                                            |
  | status        | not installed                                                                                                 |
  +-------------------------------------------------------------------------------------------------------------------------------+


  +------------------------------------------------------------------------------------------------+
  | path          | recon/domains-hosts/brute_hosts                                                |
  | name          | DNS Hostname Brute Forcer                                                      |
  | author        | Tim Tomes (@lanmaster53)                                                       |
  | version       | 1.0                                                                            |
  | last_updated  | 2019-06-24                                                                     |
  | description   | Brute forces host names using DNS. Updates the 'hosts' table with the results. |
  | required_keys | []                                                                             |
  | dependencies  | []                                                                             |
  | files         | ['hostnames.txt']                                                              |
  | status        | not installed                                                                  |
  +------------------------------------------------------------------------------------------------+


  +---------------------------------------------------------------------------------------------------------------------+
  | path          | recon/domains-hosts/builtwith                                                                       |
  | name          | BuiltWith Enumerator                                                                                |
  | author        | Tim Tomes (@lanmaster53)                                                                            |
  | version       | 1.0                                                                                                 |
  | last_updated  | 2019-06-24                                                                                          |
  | description   | Leverages the BuiltWith API to identify hosts, technologies, and contacts associated with a domain. |
  | required_keys | ['builtwith_api']                                                                                   |
  | dependencies  | []                                                                                                  |
  | files         | []                                                                                                  |
  | status        | not installed                                                                                       |
  +---------------------------------------------------------------------------------------------------------------------+


  +----------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/domains-hosts/censys_domain                                                                                            |
  | name          | Censys hosts and subdomains by domain                                                                                        |
  | author        | Censys Team                                                                                                                  |
  | version       | 2.0                                                                                                                          |
  | last_updated  | 2021-05-10                                                                                                                   |
  | description   | Retrieves the MX, SMTPS, POP3S, and HTTPS records for a domain. Updates the 'hosts' and the 'ports' tables with the results. |
  | required_keys | ['censysio_id', 'censysio_secret']                                                                                           |
  | dependencies  | ['censys>=2.0.0']                                                                                                            |
  | files         | []                                                                                                                           |
  | status        | not installed                                                                                                                |
  +----------------------------------------------------------------------------------------------------------------------------------------------+


  +-----------------------------------------------------------------------------------------------------------------------+
  | path          | recon/domains-hosts/certificate_transparency                                                          |
  | name          | Certificate Transparency Search                                                                       |
  | author        | Rich Warren (richard.warren@nccgroup.trust)                                                           |
  | version       | 1.2                                                                                                   |
  | last_updated  | 2019-09-16                                                                                            |
  | description   | Searches certificate transparency data from crt.sh, adding newly identified hosts to the hosts table. |
  | required_keys | []                                                                                                    |
  | dependencies  | []                                                                                                    |
  | files         | []                                                                                                    |
  | status        | not installed                                                                                         |
  +-----------------------------------------------------------------------------------------------------------------------+


  +---------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/domains-hosts/google_site_web                                                                             |
  | name          | Google Hostname Enumerator                                                                                      |
  | author        | Tim Tomes (@lanmaster53)                                                                                        |
  | version       | 1.0                                                                                                             |
  | last_updated  | 2019-06-24                                                                                                      |
  | description   | Harvests hosts from Google.com by using the 'site' search operator. Updates the 'hosts' table with the results. |
  | required_keys | []                                                                                                              |
  | dependencies  | []                                                                                                              |
  | files         | []                                                                                                              |
  | status        | not installed                                                                                                   |
  +---------------------------------------------------------------------------------------------------------------------------------+


  +---------------------------------------------------------------------------------------------------------------+
  | path          | recon/domains-hosts/hackertarget                                                              |
  | name          | HackerTarget Lookup                                                                           |
  | author        | Michael Henriksen (@michenriksen)                                                             |
  | version       | 1.1                                                                                           |
  | last_updated  | 2020-05-17                                                                                    |
  | description   | Uses the HackerTarget.com API to find host names. Updates the 'hosts' table with the results. |
  | required_keys | []                                                                                            |
  | dependencies  | []                                                                                            |
  | files         | []                                                                                            |
  | status        | not installed                                                                                 |
  +---------------------------------------------------------------------------------------------------------------+


  +-------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/domains-hosts/mx_spf_ip                                                                                       |
  | name          | Mail eXchange (MX) and Sender Policy Framework (SPF) Record Retriever                                               |
  | author        | Jim Becher (@jimbecher, jbecher@korelogic.com)                                                                      |
  | version       | 1.0                                                                                                                 |
  | last_updated  | 2019-06-24                                                                                                          |
  | description   | Retrieves the MX and SPF IPv4 records for a domain. Updates the 'hosts' and/or 'netblocks' tables with the results. |
  | required_keys | []                                                                                                                  |
  | dependencies  | []                                                                                                                  |
  | files         | []                                                                                                                  |
  | status        | not installed                                                                                                       |
  +-------------------------------------------------------------------------------------------------------------------------------------+


  +-----------------------------------------------------------------------------------------------+
  | path          | recon/domains-hosts/netcraft                                                  |
  | name          | Netcraft Hostname Enumerator                                                  |
  | author        | thrapt (thrapt@gmail.com)                                                     |
  | version       | 1.1                                                                           |
  | last_updated  | 2020-02-05                                                                    |
  | description   | Harvests hosts from Netcraft.com. Updates the 'hosts' table with the results. |
  | required_keys | []                                                                            |
  | dependencies  | []                                                                            |
  | files         | []                                                                            |
  | status        | not installed                                                                 |
  +-----------------------------------------------------------------------------------------------+


  +-----------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/domains-hosts/shodan_hostname                                                                                     |
  | name          | Shodan Hostname Enumerator                                                                                              |
  | author        | Tim Tomes (@lanmaster53) & Ryan Hays (@_ryanhays)                                                                       |
  | version       | 1.1                                                                                                                     |
  | last_updated  | 2020-07-01                                                                                                              |
  | description   | Harvests hosts from the Shodan API by using the 'hostname' search operator. Updates the 'hosts' table with the results. |
  | required_keys | ['shodan_api']                                                                                                          |
  | dependencies  | ['shodan']                                                                                                              |
  | files         | []                                                                                                                      |
  | status        | not installed                                                                                                           |
  +-----------------------------------------------------------------------------------------------------------------------------------------+


  +------------------------------------------------------------+
  | path          | recon/domains-hosts/spyse_subdomains       |
  | name          | Spyse Subdomain lookup                     |
  | author        | Ryan Hays                                  |
  | version       | 1.0                                        |
  | last_updated  | 2020-07-07                                 |
  | description   | Uses the Spyse API to discover subdomains. |
  | required_keys | ['spyse_api']                              |
  | dependencies  | []                                         |
  | files         | []                                         |
  | status        | not installed                              |
  +------------------------------------------------------------+


  +---------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/domains-hosts/ssl_san                                                                                                 |
  | name          | SSL SAN Lookup                                                                                                              |
  | author        | Zach Grace (@ztgrace) zgrace@403labs.com and Bryan Onel (@BryanOnel86) onel@oneleet.com                                     |
  | version       | 1.0                                                                                                                         |
  | last_updated  | 2019-06-24                                                                                                                  |
  | description   | Uses the ssltools.com API to obtain the Subject Alternative Names for a domain. Updates the 'hosts' table with the results. |
  | required_keys | []                                                                                                                          |
  | dependencies  | []                                                                                                                          |
  | files         | []                                                                                                                          |
  | status        | not installed                                                                                                               |
  +---------------------------------------------------------------------------------------------------------------------------------------------+


  +-----------------------------------------------------------------------------------------+
  | path          | recon/domains-hosts/threatcrowd                                         |
  | name          | ThreatCrowd DNS lookup                                                  |
  | author        | mike2dot0                                                               |
  | version       | 1.0                                                                     |
  | last_updated  | 2019-06-24                                                              |
  | description   | Leverages the ThreatCrowd passive DNS API to discover hosts/subdomains. |
  | required_keys | []                                                                      |
  | dependencies  | []                                                                      |
  | files         | []                                                                      |
  | status        | not installed                                                           |
  +-----------------------------------------------------------------------------------------+


  +-------------------------------------------------------------+
  | path          | recon/domains-hosts/threatminer             |
  | name          | ThreatMiner DNS lookup                      |
  | author        | Pedro Rodrigues                             |
  | version       | 1.0                                         |
  | last_updated  | 2019-06-24                                  |
  | description   | Use ThreatMiner API to discover subdomains. |
  | required_keys | []                                          |
  | dependencies  | []                                          |
  | files         | []                                          |
  | status        | not installed                               |
  +-------------------------------------------------------------+


  +---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/domains-vulnerabilities/ghdb                                                                                                                                                      |
  | name          | Google Hacking Database                                                                                                                                                                 |
  | author        | Tim Tomes (@lanmaster53)                                                                                                                                                                |
  | version       | 1.1                                                                                                                                                                                     |
  | last_updated  | 2019-06-26                                                                                                                                                                              |
  | description   | Searches for possible vulnerabilites in a domain by leveraging the Google Hacking Database (GHDB) and the 'site' search operator. Updates the 'vulnerabilities' table with the results. |
  | required_keys | []                                                                                                                                                                                      |
  | dependencies  | []                                                                                                                                                                                      |
  | files         | ['ghdb.json']                                                                                                                                                                           |
  | status        | not installed                                                                                                                                                                           |
  +---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+


  +--------------------------------------------------------------------------------------------------------------+
  | path          | recon/domains-vulnerabilities/xssed                                                          |
  | name          | XSSed Domain Lookup                                                                          |
  | author        | Micah Hoffman (@WebBreacher)                                                                 |
  | version       | 1.1                                                                                          |
  | last_updated  | 2020-10-18                                                                                   |
  | description   | Checks XSSed.com for XSS records associated with a domain and displays the first 20 results. |
  | required_keys | []                                                                                           |
  | dependencies  | []                                                                                           |
  | files         | []                                                                                           |
  | status        | not installed                                                                                |
  +--------------------------------------------------------------------------------------------------------------+


  +--------------------------------------------------------------------------------------+
  | path          | recon/hosts-domains/migrate_hosts                                    |
  | name          | Hosts to Domains Data Migrator                                       |
  | author        | Tim Tomes (@lanmaster53)                                             |
  | version       | 1.1                                                                  |
  | last_updated  | 2020-05-17                                                           |
  | description   | Adds a new domain for all the hostnames stored in the 'hosts' table. |
  | required_keys | []                                                                   |
  | dependencies  | []                                                                   |
  | files         | ['suffixes.txt']                                                     |
  | status        | not installed                                                        |
  +--------------------------------------------------------------------------------------+


  +-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/hosts-hosts/bing_ip                                                                                                                                           |
  | name          | Bing API IP Neighbor Enumerator                                                                                                                                     |
  | author        | Tim Tomes (@lanmaster53)                                                                                                                                            |
  | version       | 1.0                                                                                                                                                                 |
  | last_updated  | 2019-06-24                                                                                                                                                          |
  | description   | Leverages the Bing API and "ip:" advanced search operator to enumerate other virtual hosts sharing the same IP address. Updates the 'hosts' table with the results. |
  | required_keys | ['bing_api']                                                                                                                                                        |
  | dependencies  | []                                                                                                                                                                  |
  | files         | []                                                                                                                                                                  |
  | status        | not installed                                                                                                                                                       |
  +-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+


  +-------------------------------------------------------------------------------------------------+
  | path          | recon/hosts-hosts/censys_hostname                                               |
  | name          | Censys hosts by hostname                                                        |
  | author        | Censys Team                                                                     |
  | version       | 2.0                                                                             |
  | last_updated  | 2021-05-10                                                                      |
  | description   | Retrieves all IPs for a given hostname. Updates the "hosts" and "ports" tables. |
  | required_keys | ['censysio_id', 'censysio_secret']                                              |
  | dependencies  | ['censys>=2.0.0']                                                               |
  | files         | []                                                                              |
  | status        | not installed                                                                   |
  +-------------------------------------------------------------------------------------------------+


  +-----------------------------------------------------------------------------------------------------------+
  | path          | recon/hosts-hosts/censys_ip                                                               |
  | name          | Censys ports by IP                                                                        |
  | author        | Censys Team                                                                               |
  | version       | 2.0                                                                                       |
  | last_updated  | 2021-05-10                                                                                |
  | description   | Retrieves the open ports for each IP address. Updates the 'ports' table with the results. |
  | required_keys | ['censysio_id', 'censysio_secret']                                                        |
  | dependencies  | ['censys>=2.0.0']                                                                         |
  | files         | []                                                                                        |
  | status        | not installed                                                                             |
  +-----------------------------------------------------------------------------------------------------------+


  +------------------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/hosts-hosts/censys_query                                                                                                       |
  | name          | Censys hosts by search terms                                                                                                         |
  | author        | Censys Team                                                                                                                          |
  | version       | 2.0                                                                                                                                  |
  | last_updated  | 2021-05-10                                                                                                                           |
  | description   | Retrieves details for hosts matching an arbitrary Censys query. Updates the 'hosts', 'domains', and 'ports' tables with the results. |
  | required_keys | ['censysio_id', 'censysio_secret']                                                                                                   |
  | dependencies  | ['censys>=2.0.0']                                                                                                                    |
  | files         | []                                                                                                                                   |
  | status        | not installed                                                                                                                        |
  +------------------------------------------------------------------------------------------------------------------------------------------------------+


  +-------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/hosts-hosts/ipinfodb                                                                                    |
  | name          | IPInfoDB GeoIP                                                                                                |
  | author        | Tim Tomes (@lanmaster53)                                                                                      |
  | version       | 1.1                                                                                                           |
  | last_updated  | 2020-06-08                                                                                                    |
  | description   | Leverages the ipinfodb.com API to geolocate a host by IP address. Updates the 'hosts' table with the results. |
  | required_keys | ['ipinfodb_api']                                                                                              |
  | dependencies  | []                                                                                                            |
  | files         | []                                                                                                            |
  | status        | not installed                                                                                                 |
  +-------------------------------------------------------------------------------------------------------------------------------+


  +------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/hosts-hosts/ipstack                                                                                    |
  | name          | ipstack                                                                                                      |
  | author        | Siarhei Harbachou (Tech.Insiders), Gerrit Helm (G) and Tim Tomes (@lanmaster53)                              |
  | version       | 1.0                                                                                                          |
  | last_updated  | 2019-06-24                                                                                                   |
  | description   | Leverages the ipstack.com API to geolocate a host by IP address. Updates the 'hosts' table with the results. |
  | required_keys | ['ipstack_api']                                                                                              |
  | dependencies  | []                                                                                                           |
  | files         | []                                                                                                           |
  | status        | not installed                                                                                                |
  +------------------------------------------------------------------------------------------------------------------------------+


  +-------------------------------------------------------------------------------------------------+
  | path          | recon/hosts-hosts/resolve                                                       |
  | name          | Hostname Resolver                                                               |
  | author        | Tim Tomes (@lanmaster53)                                                        |
  | version       | 1.0                                                                             |
  | last_updated  | 2019-06-24                                                                      |
  | description   | Resolves the IP address for a host. Updates the 'hosts' table with the results. |
  | required_keys | []                                                                              |
  | dependencies  | []                                                                              |
  | files         | []                                                                              |
  | status        | not installed                                                                   |
  +-------------------------------------------------------------------------------------------------+


  +------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/hosts-hosts/reverse_resolve                                                                                  |
  | name          | Reverse Resolver                                                                                                   |
  | author        | John Babio (@3vi1john), @vulp1n3, and Tim Tomes (@lanmaster53)                                                     |
  | version       | 1.0                                                                                                                |
  | last_updated  | 2019-06-24                                                                                                         |
  | description   | Conducts a reverse lookup for each IP address to resolve the hostname. Updates the 'hosts' table with the results. |
  | required_keys | []                                                                                                                 |
  | dependencies  | []                                                                                                                 |
  | files         | []                                                                                                                 |
  | status        | not installed                                                                                                      |
  +------------------------------------------------------------------------------------------------------------------------------------+


  +----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/hosts-hosts/ssltools                                                                                                                                                                                 |
  | name          | SSLTools.com Host Name Lookups                                                                                                                                                                             |
  | author        | Tim Maletic (borrowing from the ssl_san module by Zach Graces)                                                                                                                                             |
  | version       | 1.0                                                                                                                                                                                                        |
  | last_updated  | 2019-06-24                                                                                                                                                                                                 |
  | description   | Uses the ssltools.com site to obtain host names from a site's SSL certificate metadata to update the 'hosts' table.  Security issues with the certificate trust are pushed to the 'vulnerabilities' table. |
  | required_keys | []                                                                                                                                                                                                         |
  | dependencies  | []                                                                                                                                                                                                         |
  | files         | []                                                                                                                                                                                                         |
  | status        | not installed                                                                                                                                                                                              |
  +----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+


  +---------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/hosts-hosts/virustotal                                                                              |
  | name          | Virustotal domains extractor                                                                              |
  | author        | USSC (thanks @jevalenciap)                                                                                |
  | version       | 1.0                                                                                                       |
  | last_updated  | 2019-06-24                                                                                                |
  | description   | Harvests domains from the Virustotal by using the report API. Updates the 'hosts' table with the results. |
  | required_keys | ['virustotal_api']                                                                                        |
  | dependencies  | []                                                                                                        |
  | files         | []                                                                                                        |
  | status        | not installed                                                                                             |
  +---------------------------------------------------------------------------------------------------------------------------+


  +----------------------------------------------------------------------------------------+
  | path          | recon/hosts-locations/migrate_hosts                                    |
  | name          | Hosts to Locations Data Migrator                                       |
  | author        | Tim Tomes (@lanmaster53)                                               |
  | version       | 1.0                                                                    |
  | last_updated  | 2019-06-24                                                             |
  | description   | Adds a new location for all the locations stored in the 'hosts' table. |
  | required_keys | []                                                                     |
  | dependencies  | []                                                                     |
  | files         | []                                                                     |
  | status        | not installed                                                          |
  +----------------------------------------------------------------------------------------+


  +-------------------------------------------------------------------------------------+
  | path          | recon/hosts-ports/binaryedge                                        |
  | name          | BinaryEdge.io Ports lookup                                          |
  | author        | Ryan Hays                                                           |
  | version       | 1.0                                                                 |
  | last_updated  | 2019-06-24                                                          |
  | description   | Uses the BinaryEdge API to discover open services for IP Addresses. |
  | required_keys | ['binaryedge_api']                                                  |
  | dependencies  | []                                                                  |
  | files         | []                                                                  |
  | status        | not installed                                                       |
  +-------------------------------------------------------------------------------------+


  +----------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/hosts-ports/shodan_ip                                                                                                  |
  | name          | Shodan IP Enumerator                                                                                                         |
  | author        | Tim Tomes (@lanmaster53) and Matt Puckett (@t3lc0) & Ryan Hays (@_ryanhays)                                                  |
  | version       | 1.2                                                                                                                          |
  | last_updated  | 2020-07-01                                                                                                                   |
  | description   | Harvests port information from the Shodan API by using the 'ip' search operator. Updates the 'ports' table with the results. |
  | required_keys | ['shodan_api']                                                                                                               |
  | dependencies  | ['shodan']                                                                                                                   |
  | files         | []                                                                                                                           |
  | status        | not installed                                                                                                                |
  +----------------------------------------------------------------------------------------------------------------------------------------------+


  +-----------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/locations-locations/geocode                                                                                 |
  | name          | Address Geocoder                                                                                                  |
  | author        | Quentin Kaiser (contact@quentinkaiser.be)                                                                         |
  | version       | 1.0                                                                                                               |
  | last_updated  | 2019-06-24                                                                                                        |
  | description   | Queries the Google Maps API to obtain coordinates for an address. Updates the 'locations' table with the results. |
  | required_keys | ['google_api']                                                                                                    |
  | dependencies  | []                                                                                                                |
  | files         | []                                                                                                                |
  | status        | not installed                                                                                                     |
  +-----------------------------------------------------------------------------------------------------------------------------------+


  +------------------------------------------------------------------------------------+
  | path          | recon/locations-locations/reverse_geocode                          |
  | name          | Reverse Geocoder                                                   |
  | author        | Quentin Kaiser (contact@quentinkaiser.be)                          |
  | version       | 1.0                                                                |
  | last_updated  | 2019-06-24                                                         |
  | description   | Queries the Google Maps API to obtain an address from coordinates. |
  | required_keys | ['google_api']                                                     |
  | dependencies  | []                                                                 |
  | files         | []                                                                 |
  | status        | not installed                                                      |
  +------------------------------------------------------------------------------------+


  +-------------------------------------------------------------------------------------+
  | path          | recon/locations-pushpins/flickr                                     |
  | name          | Flickr Geolocation Search                                           |
  | author        | Tim Tomes (@lanmaster53)                                            |
  | version       | 1.0                                                                 |
  | last_updated  | 2019-06-24                                                          |
  | description   | Searches Flickr for media in the specified proximity to a location. |
  | required_keys | ['flickr_api']                                                      |
  | dependencies  | []                                                                  |
  | files         | []                                                                  |
  | status        | not installed                                                       |
  +-------------------------------------------------------------------------------------+


  +-------------------------------------------------------------------------------------+
  | path          | recon/locations-pushpins/shodan                                     |
  | name          | Shodan Geolocation Search                                           |
  | author        | Tim Tomes (@lanmaster53) & Ryan Hays (@_ryanhays)                   |
  | version       | 1.1                                                                 |
  | last_updated  | 2020-07-07                                                          |
  | description   | Searches Shodan for media in the specified proximity to a location. |
  | required_keys | ['shodan_api']                                                      |
  | dependencies  | ['shodan']                                                          |
  | files         | []                                                                  |
  | status        | not installed                                                       |
  +-------------------------------------------------------------------------------------+


  +--------------------------------------------------------------------------------------+
  | path          | recon/locations-pushpins/twitter                                     |
  | name          | Twitter Geolocation Search                                           |
  | author        | Tim Tomes (@lanmaster53)                                             |
  | version       | 1.1                                                                  |
  | last_updated  | 2019-10-17                                                           |
  | description   | Searches Twitter for media in the specified proximity to a location. |
  | required_keys | ['twitter_api', 'twitter_secret']                                    |
  | dependencies  | []                                                                   |
  | files         | []                                                                   |
  | status        | not installed                                                        |
  +--------------------------------------------------------------------------------------+


  +----------------------------------------------------------------------------------------------+
  | path          | recon/locations-pushpins/youtube                                             |
  | name          | YouTube Geolocation Search                                                   |
  | author        | Tim Tomes (@lanmaster53)                                                     |
  | version       | 1.2                                                                          |
  | last_updated  | 2020-09-02                                                                   |
  | description   | Searches the YouTube API for media in the specified proximity to a location. |
  | required_keys | ['google_api']                                                               |
  | dependencies  | []                                                                           |
  | files         | []                                                                           |
  | status        | not installed                                                                |
  +----------------------------------------------------------------------------------------------+


  +--------------------------------------------------------------------------------------------------------------------+
  | path          | recon/netblocks-companies/censys_netblock_company                                                  |
  | name          | Censys companies by netblock                                                                       |
  | author        | Censys Team                                                                                        |
  | version       | 2.0                                                                                                |
  | last_updated  | 2021-05-11                                                                                         |
  | description   | Retrieves organizations for a company's netblocks. Updates the 'companies' table with the results. |
  | required_keys | ['censysio_id', 'censysio_secret']                                                                 |
  | dependencies  | ['censys>=2.0.0']                                                                                  |
  | files         | []                                                                                                 |
  | status        | not installed                                                                                      |
  +--------------------------------------------------------------------------------------------------------------------+


  +--------------------------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/netblocks-companies/whois_orgs                                                                                                         |
  | name          | Whois Company Harvester                                                                                                                      |
  | author        | Tim Tomes (@lanmaster53)                                                                                                                     |
  | version       | 1.0                                                                                                                                          |
  | last_updated  | 2019-06-24                                                                                                                                   |
  | description   | Uses the ARIN Whois RWS to harvest Companies data from whois queries for the given netblock. Updates the 'companies' table with the results. |
  | required_keys | []                                                                                                                                           |
  | dependencies  | []                                                                                                                                           |
  | files         | []                                                                                                                                           |
  | status        | not installed                                                                                                                                |
  +--------------------------------------------------------------------------------------------------------------------------------------------------------------+


  +------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/netblocks-hosts/censys_netblock                                                                  |
  | name          | Censys hosts by netblock                                                                               |
  | author        | Censys Team                                                                                            |
  | version       | 2.0                                                                                                    |
  | last_updated  | 2021-05-10                                                                                             |
  | description   | Retrieves hosts and ports for a neyblock. Updates the 'hosts' and the 'ports' tables with the results. |
  | required_keys | ['censysio_id', 'censysio_secret']                                                                     |
  | dependencies  | ['censys>=2.0.0']                                                                                      |
  | files         | []                                                                                                     |
  | status        | not installed                                                                                          |
  +------------------------------------------------------------------------------------------------------------------------+


  +------------------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/netblocks-hosts/reverse_resolve                                                                                                |
  | name          | Reverse Resolver                                                                                                                     |
  | author        | John Babio (@3vi1john)                                                                                                               |
  | version       | 1.0                                                                                                                                  |
  | last_updated  | 2019-06-24                                                                                                                           |
  | description   | Conducts a reverse lookup for each of a netblock's IP addresses to resolve the hostname. Updates the 'hosts' table with the results. |
  | required_keys | []                                                                                                                                   |
  | dependencies  | []                                                                                                                                   |
  | files         | []                                                                                                                                   |
  | status        | not installed                                                                                                                        |
  +------------------------------------------------------------------------------------------------------------------------------------------------------+


  +------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/netblocks-hosts/shodan_net                                                                                   |
  | name          | Shodan Network Enumerator                                                                                          |
  | author        | Mike Siegel and Tim Tomes (@lanmaster53) & Ryan Hays (@_ryanhays)                                                  |
  | version       | 1.2                                                                                                                |
  | last_updated  | 2020-07-21                                                                                                         |
  | description   | Harvests hosts from the Shodan API by using the 'net' search operator. Updates the 'hosts' table with the results. |
  | required_keys | ['shodan_api']                                                                                                     |
  | dependencies  | ['shodan']                                                                                                         |
  | files         | []                                                                                                                 |
  | status        | not installed                                                                                                      |
  +------------------------------------------------------------------------------------------------------------------------------------+


  +---------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/netblocks-hosts/virustotal                                                                          |
  | name          | Virustotal domains extractor                                                                              |
  | author        | USSC (thanks @jevalenciap)                                                                                |
  | version       | 1.0                                                                                                       |
  | last_updated  | 2019-06-24                                                                                                |
  | description   | Harvests domains from the Virustotal by using the report API. Updates the 'hosts' table with the results. |
  | required_keys | ['virustotal_api']                                                                                        |
  | dependencies  | []                                                                                                        |
  | files         | []                                                                                                        |
  | status        | not installed                                                                                             |
  +---------------------------------------------------------------------------------------------------------------------------+


  +-----------------------------------------------------------------------------------------------------------------------+
  | path          | recon/netblocks-ports/census_2012                                                                     |
  | name          | Internet Census 2012 Lookup                                                                           |
  | author        | Tim Tomes (@lanmaster53)                                                                              |
  | version       | 1.0                                                                                                   |
  | last_updated  | 2019-06-24                                                                                            |
  | description   | Queries the Internet Census 2012 data through Exfiltrated.com to enumerate open ports for a netblock. |
  | required_keys | []                                                                                                    |
  | dependencies  | []                                                                                                    |
  | files         | []                                                                                                    |
  | status        | not installed                                                                                         |
  +-----------------------------------------------------------------------------------------------------------------------+


  +-------------------------------------------------------------------------------------+
  | path          | recon/netblocks-ports/censysio                                      |
  | name          | Censys.io Netblock Enumerator                                       |
  | author        | John Askew (https://bitbucket.org/skew)                             |
  | version       | 1.0                                                                 |
  | last_updated  | 2019-06-24                                                          |
  | description   | Queries the censys.io API to enumerate information about netblocks. |
  | required_keys | ['censysio_id', 'censysio_secret']                                  |
  | dependencies  | []                                                                  |
  | files         | []                                                                  |
  | status        | not installed                                                       |
  +-------------------------------------------------------------------------------------+


  +------------------------------------------------------------------------------------+
  | path          | recon/ports-hosts/migrate_ports                                    |
  | name          | Ports to Hosts Data Migrator                                       |
  | author        | Tim Tomes (@lanmaster53)                                           |
  | version       | 1.0                                                                |
  | last_updated  | 2019-06-24                                                         |
  | description   | Adds a new host for all the hostnames stored in the 'ports' table. |
  | required_keys | []                                                                 |
  | dependencies  | []                                                                 |
  | files         | []                                                                 |
  | status        | not installed                                                      |
  +------------------------------------------------------------------------------------+


  +---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/ports-hosts/ssl_scan                                                                                                                                                                                      |
  | name          | SSL Scanner SAN Lookup                                                                                                                                                                                          |
  | author        | Ryan Hays (@_ryanhays)                                                                                                                                                                                          |
  | version       | 1.0                                                                                                                                                                                                             |
  | last_updated  | 2020-04-13                                                                                                                                                                                                      |
  | description   | Queries the ports table to build a list of IP Address:Ports. It then connects to each service updating the Ports table with the certificate common name and then adds the Subject Alt Names to the hosts table. |
  | required_keys | []                                                                                                                                                                                                              |
  | dependencies  | []                                                                                                                                                                                                              |
  | files         | []                                                                                                                                                                                                              |
  | status        | not installed                                                                                                                                                                                                   |
  +---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+


  +------------------------------------------------------------------------------------------+
  | path          | recon/profiles-contacts/bing_linkedin_contacts                           |
  | name          | Bing LinkedIn Profile Contact Harvester                                  |
  | author        | Cam Barts (@cam-barts)                                                   |
  | version       | 1.1                                                                      |
  | last_updated  | 2019-10-08                                                               |
  | description   | Harvests Basic Contact Information from Bing based on LinkedIn profiles. |
  | required_keys | ['bing_api']                                                             |
  | dependencies  | []                                                                       |
  | files         | []                                                                       |
  | status        | not installed                                                            |
  +------------------------------------------------------------------------------------------+


  +-------------------------------------------------------------------------------------------+
  | path          | recon/profiles-contacts/dev_diver                                         |
  | name          | Dev Diver Repository Activity Examiner                                    |
  | author        | Micah Hoffman (@WebBreacher)                                              |
  | version       | 1.1                                                                       |
  | last_updated  | 2020-05-15                                                                |
  | description   | Searches public code repositories for information about a given username. |
  | required_keys | []                                                                        |
  | dependencies  | []                                                                        |
  | files         | []                                                                        |
  | status        | not installed                                                             |
  +-------------------------------------------------------------------------------------------+


  +---------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/profiles-contacts/github_users                                                                            |
  | name          | Github Profile Harvester                                                                                        |
  | author        | Tim Tomes (@lanmaster53)                                                                                        |
  | version       | 1.0                                                                                                             |
  | last_updated  | 2019-06-24                                                                                                      |
  | description   | Uses the Github API to gather user info from harvested profiles. Updates the 'contacts' table with the results. |
  | required_keys | ['github_api']                                                                                                  |
  | dependencies  | []                                                                                                              |
  | files         | []                                                                                                              |
  | status        | not installed                                                                                                   |
  +---------------------------------------------------------------------------------------------------------------------------------+


  +-----------------------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/profiles-profiles/namechk                                                                                                           |
  | name          | NameChk.com Username Validator                                                                                                            |
  | author        | Tim Tomes (@lanmaster53), thrapt (thrapt@gmail.com) and Ryan Hays (@_ryanhays)                                                            |
  | version       | 1.0                                                                                                                                       |
  | last_updated  | 2019-06-24                                                                                                                                |
  | description   | Leverages NameChk.com API to validate the existance of usernames on specific web sites and updates the 'profiles' table with the results. |
  | required_keys | ['namechk_api']                                                                                                                           |
  | dependencies  | []                                                                                                                                        |
  | files         | []                                                                                                                                        |
  | status        | not installed                                                                                                                             |
  +-----------------------------------------------------------------------------------------------------------------------------------------------------------+


  +----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/profiles-profiles/profiler                                                                                                                                                                     |
  | name          | OSINT HUMINT Profile Collector                                                                                                                                                                       |
  | author        | Micah Hoffman (@WebBreacher)                                                                                                                                                                         |
  | version       | 1.0                                                                                                                                                                                                  |
  | last_updated  | 2019-06-24                                                                                                                                                                                           |
  | description   | Takes each username from the profiles table and searches a variety of web sites for those users. The list of valid sites comes from the parent project at https://github.com/WebBreacher/WhatsMyName |
  | required_keys | []                                                                                                                                                                                                   |
  | dependencies  | []                                                                                                                                                                                                   |
  | files         | []                                                                                                                                                                                                   |
  | status        | not installed                                                                                                                                                                                        |
  +----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+


  +----------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/profiles-profiles/twitter_mentioned                                                                                    |
  | name          | Twitter Mentioned                                                                                                            |
  | author        | Robert Frost (@frosty_1313, frosty[at]unluckyfrosty.net)                                                                     |
  | version       | 1.0                                                                                                                          |
  | last_updated  | 2019-06-24                                                                                                                   |
  | description   | Leverages the Twitter API to enumerate users that mentioned the given handle. Updates the 'profiles' table with the results. |
  | required_keys | ['twitter_api', 'twitter_secret']                                                                                            |
  | dependencies  | []                                                                                                                           |
  | files         | []                                                                                                                           |
  | status        | not installed                                                                                                                |
  +----------------------------------------------------------------------------------------------------------------------------------------------+


  +------------------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/profiles-profiles/twitter_mentions                                                                                             |
  | name          | Twitter Mentions                                                                                                                     |
  | author        | Robert Frost (@frosty_1313, frosty[at]unluckyfrosty.net)                                                                             |
  | version       | 1.0                                                                                                                                  |
  | last_updated  | 2019-06-24                                                                                                                           |
  | description   | Leverages the Twitter API to enumerate users that were mentioned by the given handle. Updates the 'profiles' table with the results. |
  | required_keys | ['twitter_api', 'twitter_secret']                                                                                                    |
  | dependencies  | []                                                                                                                                   |
  | files         | []                                                                                                                                   |
  | status        | not installed                                                                                                                        |
  +------------------------------------------------------------------------------------------------------------------------------------------------------+


  +----------------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/profiles-repositories/github_repos                                                                                           |
  | name          | Github Code Enumerator                                                                                                             |
  | author        | Tim Tomes (@lanmaster53)                                                                                                           |
  | version       | 1.1                                                                                                                                |
  | last_updated  | 2020-05-15                                                                                                                         |
  | description   | Uses the Github API to enumerate repositories and gists owned by a Github user. Updates the 'repositories' table with the results. |
  | required_keys | ['github_api']                                                                                                                     |
  | dependencies  | []                                                                                                                                 |
  | files         | []                                                                                                                                 |
  | status        | not installed                                                                                                                      |
  +----------------------------------------------------------------------------------------------------------------------------------------------------+


  +-------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/repositories-profiles/github_commits                                                                          |
  | name          | Github Commit Searcher                                                                                              |
  | author        | Michael Henriksen (@michenriksen)                                                                                   |
  | version       | 1.0                                                                                                                 |
  | last_updated  | 2019-06-24                                                                                                          |
  | description   | Uses the Github API to gather user profiles from repository commits. Updates the 'profiles' table with the results. |
  | required_keys | ['github_api']                                                                                                      |
  | dependencies  | []                                                                                                                  |
  | files         | []                                                                                                                  |
  | status        | not installed                                                                                                       |
  +-------------------------------------------------------------------------------------------------------------------------------------+


  +--------------------------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/repositories-vulnerabilities/gists_search                                                                                              |
  | name          | Github Gist Searcher                                                                                                                         |
  | author        | Tim Tomes (@lanmaster53)                                                                                                                     |
  | version       | 1.0                                                                                                                                          |
  | last_updated  | 2019-06-24                                                                                                                                   |
  | description   | Uses the Github API to download and search Gists for possible information disclosures. Updates the 'vulnerabilities' table with the results. |
  | required_keys | []                                                                                                                                           |
  | dependencies  | []                                                                                                                                           |
  | files         | ['gist_keywords.txt']                                                                                                                        |
  | status        | not installed                                                                                                                                |
  +--------------------------------------------------------------------------------------------------------------------------------------------------------------+


  +-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | recon/repositories-vulnerabilities/github_dorks                                                                                                                                           |
  | name          | Github Dork Analyzer                                                                                                                                                                      |
  | author        | Tim Tomes (@lanmaster53)                                                                                                                                                                  |
  | version       | 1.0                                                                                                                                                                                       |
  | last_updated  | 2019-06-24                                                                                                                                                                                |
  | description   | Uses the Github API to search for possible vulnerabilites in source code by leveraging Github Dorks and the 'repo' search operator. Updates the 'vulnerabilities' table with the results. |
  | required_keys | ['github_api']                                                                                                                                                                            |
  | dependencies  | []                                                                                                                                                                                        |
  | files         | ['github_dorks.txt']                                                                                                                                                                      |
  | status        | not installed                                                                                                                                                                             |
  +-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+


  +-----------------------------------------------------------------------------+
  | path          | reporting/csv                                               |
  | name          | CSV File Creator                                            |
  | author        | Tim Tomes (@lanmaster53)                                    |
  | version       | 1.0                                                         |
  | last_updated  | 2019-06-24                                                  |
  | description   | Creates a CSV file containing the specified harvested data. |
  | required_keys | []                                                          |
  | dependencies  | []                                                          |
  | files         | []                                                          |
  | status        | not installed                                               |
  +-----------------------------------------------------------------------------+


  +------------------------------------------+
  | path          | reporting/html           |
  | name          | HTML Report Generator    |
  | author        | Tim Tomes (@lanmaster53) |
  | version       | 1.0                      |
  | last_updated  | 2019-06-24               |
  | description   | Creates an HTML report.  |
  | required_keys | []                       |
  | dependencies  | []                       |
  | files         | ['template_html.html']   |
  | status        | not installed            |
  +------------------------------------------+


  +----------------------------------------+
  | path          | reporting/json         |
  | name          | JSON Report Generator  |
  | author        | Paul (@PaulWebSec)     |
  | version       | 1.0                    |
  | last_updated  | 2019-06-24             |
  | description   | Creates a JSON report. |
  | required_keys | []                     |
  | dependencies  | []                     |
  | files         | []                     |
  | status        | not installed          |
  +----------------------------------------+


  +--------------------------------------------------------------------------------+
  | path          | reporting/list                                                 |
  | name          | List Creator                                                   |
  | author        | Tim Tomes (@lanmaster53)                                       |
  | version       | 1.0                                                            |
  | last_updated  | 2019-06-24                                                     |
  | description   | Creates a file containing a list of records from the database. |
  | required_keys | []                                                             |
  | dependencies  | []                                                             |
  | files         | []                                                             |
  | status        | not installed                                                  |
  +--------------------------------------------------------------------------------+


  +--------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
  | path          | reporting/proxifier                                                                                                                                      |
  | name          | Proxifier                                                                                                                                                |
  | author        | AverageSecurityGuy (@averagesecguy)                                                                                                                      |
  | version       | 1.0                                                                                                                                                      |
  | last_updated  | 2019-06-24                                                                                                                                               |
  | description   | Requests URLs from the database for the purpose of populating an inline proxy. Requires that the global proxy option be set prior to running the module. |
  | required_keys | []                                                                                                                                                       |
  | dependencies  | []                                                                                                                                                       |
  | files         | []                                                                                                                                                       |
  | status        | not installed                                                                                                                                            |
  +--------------------------------------------------------------------------------------------------------------------------------------------------------------------------+


  +----------------------------------------------------------------------------------------------------+
  | path          | reporting/pushpin                                                                  |
  | name          | PushPin Report Generator                                                           |
  | author        | Tim Tomes (@lanmaster53)                                                           |
  | version       | 1.0                                                                                |
  | last_updated  | 2019-06-24                                                                         |
  | description   | Creates HTML media and map reports for all of the PushPins stored in the database. |
  | required_keys | ['google_api']                                                                     |
  | dependencies  | []                                                                                 |
  | files         | ['template_media.html', 'template_map.html']                                       |
  | status        | not installed                                                                      |
  +----------------------------------------------------------------------------------------------------+


  +---------------------------------------------------------------------------------------+
  | path          | reporting/xlsx                                                        |
  | name          | XLSX File Creator                                                     |
  | author        | Tim Tomes (@lanmaster53)                                              |
  | version       | 1.0                                                                   |
  | last_updated  | 2019-06-24                                                            |
  | description   | Creates an Excel compatible XLSX file containing the entire data set. |
  | required_keys | []                                                                    |
  | dependencies  | []                                                                    |
  | files         | []                                                                    |
  | status        | not installed                                                         |
  +---------------------------------------------------------------------------------------+


  +-----------------------------------------------------------------------+
  | path          | reporting/xml                                         |
  | name          | XML Report Generator                                  |
  | author        | Eric Humphries (@e2fsck) and Tim Tomes (@lanmaster53) |
  | version       | 1.1                                                   |
  | last_updated  | 2019-06-24                                            |
  | description   | Creates an XML report.                                |
  | required_keys | []                                                    |
  | dependencies  | []                                                    |
  | files         | []                                                    |
  | status        | not installed                                         |
  +-----------------------------------------------------------------------+

[recon-ng][default] > marketplace search hackertarget
[*] Searching module index for 'hackertarget'...

  +---------------------------------------------------------------------------------+
  |               Path               | Version |     Status    |  Updated   | D | K |
  +---------------------------------------------------------------------------------+
  | recon/domains-hosts/hackertarget | 1.1     | not installed | 2020-05-17 |   |   |
  +---------------------------------------------------------------------------------+

  D = Has dependencies. See info for details.
  K = Requires keys. See info for details.

[recon-ng][default] > marketplace install hackertarget
[*] Module installed: recon/domains-hosts/hackertarget
[*] Reloading modules...
[recon-ng][default] > marketplace install all
[*] Module installed: discovery/info_disclosure/cache_snoop
[*] Module installed: discovery/info_disclosure/interesting_files
[*] Module installed: exploitation/injection/command_injector
[*] Module installed: exploitation/injection/xpath_bruter
[*] Module installed: import/csv_file
[*] Module installed: import/list
[*] Module installed: import/masscan
[*] Module installed: import/nmap
[*] Module installed: recon/companies-contacts/bing_linkedin_cache
[*] Module installed: recon/companies-contacts/censys_email_address
[*] Module installed: recon/companies-contacts/pen
[*] Module installed: recon/companies-domains/censys_subdomains
[*] Module installed: recon/companies-domains/pen
[*] Module installed: recon/companies-domains/viewdns_reverse_whois
[*] Module installed: recon/companies-domains/whoxy_dns
[*] Module installed: recon/companies-hosts/censys_org
[*] Module installed: recon/companies-hosts/censys_tls_subjects
[*] Module installed: recon/companies-multi/github_miner
[*] Module installed: recon/companies-multi/shodan_org
[*] Module installed: recon/companies-multi/whois_miner
[*] Module installed: recon/contacts-contacts/abc
[*] Module installed: recon/contacts-contacts/mailtester
[*] Module installed: recon/contacts-contacts/mangle
[*] Module installed: recon/contacts-contacts/unmangle
[*] Module installed: recon/contacts-credentials/hibp_breach
[*] Module installed: recon/contacts-credentials/hibp_paste
[*] Module installed: recon/contacts-credentials/scylla
[*] Module installed: recon/contacts-domains/migrate_contacts
[*] Module installed: recon/contacts-profiles/fullcontact
[*] Module installed: recon/credentials-credentials/adobe
[*] Module installed: recon/credentials-credentials/bozocrack
[*] Module installed: recon/credentials-credentials/hashes_org
[*] Module installed: recon/domains-companies/censys_companies
[*] Module installed: recon/domains-companies/pen
[*] Module installed: recon/domains-companies/whoxy_whois
[*] Module installed: recon/domains-contacts/hunter_io
[*] Module installed: recon/domains-contacts/metacrawler
[*] Module installed: recon/domains-contacts/pen
[*] Module installed: recon/domains-contacts/pgp_search
[*] Module installed: recon/domains-contacts/whois_pocs
[*] Module installed: recon/domains-contacts/wikileaker
[*] Module installed: recon/domains-credentials/pwnedlist/account_creds
[*] Module installed: recon/domains-credentials/pwnedlist/api_usage
[*] Module installed: recon/domains-credentials/pwnedlist/domain_creds
[*] Module installed: recon/domains-credentials/pwnedlist/domain_ispwned
[*] Module installed: recon/domains-credentials/pwnedlist/leak_lookup
[*] Module installed: recon/domains-credentials/pwnedlist/leaks_dump
[*] Module installed: recon/domains-credentials/scylla
[*] Module installed: recon/domains-domains/brute_suffix
[*] Module installed: recon/domains-hosts/binaryedge
[*] Module installed: recon/domains-hosts/bing_domain_api
[*] Module installed: recon/domains-hosts/bing_domain_web
[*] Module installed: recon/domains-hosts/brute_hosts
[*] Module installed: recon/domains-hosts/builtwith
[*] Module installed: recon/domains-hosts/censys_domain
[*] Module installed: recon/domains-hosts/certificate_transparency
[*] Module installed: recon/domains-hosts/google_site_web
[*] Module installed: recon/domains-hosts/hackertarget
[*] Module installed: recon/domains-hosts/mx_spf_ip
[*] Module installed: recon/domains-hosts/netcraft
[*] Module installed: recon/domains-hosts/shodan_hostname
[*] Module installed: recon/domains-hosts/spyse_subdomains
[*] Module installed: recon/domains-hosts/ssl_san
[*] Module installed: recon/domains-hosts/threatcrowd
[*] Module installed: recon/domains-hosts/threatminer
[*] Module installed: recon/domains-vulnerabilities/ghdb
[*] Module installed: recon/domains-vulnerabilities/xssed
[*] Module installed: recon/hosts-domains/migrate_hosts
[*] Module installed: recon/hosts-hosts/bing_ip
[*] Module installed: recon/hosts-hosts/censys_hostname
[*] Module installed: recon/hosts-hosts/censys_ip
[*] Module installed: recon/hosts-hosts/censys_query
[*] Module installed: recon/hosts-hosts/ipinfodb
[*] Module installed: recon/hosts-hosts/ipstack
[*] Module installed: recon/hosts-hosts/resolve
[*] Module installed: recon/hosts-hosts/reverse_resolve
[*] Module installed: recon/hosts-hosts/ssltools
[*] Module installed: recon/hosts-hosts/virustotal
[*] Module installed: recon/hosts-locations/migrate_hosts
[*] Module installed: recon/hosts-ports/binaryedge
[*] Module installed: recon/hosts-ports/shodan_ip
[*] Module installed: recon/locations-locations/geocode
[*] Module installed: recon/locations-locations/reverse_geocode
[*] Module installed: recon/locations-pushpins/flickr
[*] Module installed: recon/locations-pushpins/shodan
[*] Module installed: recon/locations-pushpins/twitter
[*] Module installed: recon/locations-pushpins/youtube
[*] Module installed: recon/netblocks-companies/censys_netblock_company
[*] Module installed: recon/netblocks-companies/whois_orgs
[*] Module installed: recon/netblocks-hosts/censys_netblock
[*] Module installed: recon/netblocks-hosts/reverse_resolve
[*] Module installed: recon/netblocks-hosts/shodan_net
[*] Module installed: recon/netblocks-hosts/virustotal
[*] Module installed: recon/netblocks-ports/census_2012
[*] Module installed: recon/netblocks-ports/censysio
[*] Module installed: recon/ports-hosts/migrate_ports
[*] Module installed: recon/ports-hosts/ssl_scan
[*] Module installed: recon/profiles-contacts/bing_linkedin_contacts
[*] Module installed: recon/profiles-contacts/dev_diver
[*] Module installed: recon/profiles-contacts/github_users
[*] Module installed: recon/profiles-profiles/namechk
[*] Module installed: recon/profiles-profiles/profiler
[*] Module installed: recon/profiles-profiles/twitter_mentioned
[*] Module installed: recon/profiles-profiles/twitter_mentions
[*] Module installed: recon/profiles-repositories/github_repos
[*] Module installed: recon/repositories-profiles/github_commits
[*] Module installed: recon/repositories-vulnerabilities/gists_search
[*] Module installed: recon/repositories-vulnerabilities/github_dorks
[*] Module installed: reporting/csv
[*] Module installed: reporting/html
[*] Module installed: reporting/json
[*] Module installed: reporting/list
[*] Module installed: reporting/proxifier
[*] Module installed: reporting/pushpin
[*] Module installed: reporting/xlsx
[*] Module installed: reporting/xml
[*] Reloading modules...
[!] 'hibp_api' key not set. hibp_breach module will likely fail at runtime. See 'keys add'.
[!] 'hibp_api' key not set. hibp_paste module will likely fail at runtime. See 'keys add'.
[!] Module 'recon/netblocks-companies/censys_netblock_company' disabled. Dependency required: ''censys''.
[!] 'bing_api' key not set. bing_linkedin_contacts module will likely fail at runtime. See 'keys add'.
[!] 'github_api' key not set. github_users module will likely fail at runtime. See 'keys add'.
[!] Invalid syntax.
[!] Module 'recon/domains-hosts/spyse_subdomains' disabled.
[!] 'bing_api' key not set. bing_domain_api module will likely fail at runtime. See 'keys add'.
[!] 'builtwith_api' key not set. builtwith module will likely fail at runtime. See 'keys add'.
[!] Module 'recon/domains-hosts/censys_domain' disabled. Dependency required: ''censys''.
[!] 'binaryedge_api' key not set. binaryedge module will likely fail at runtime. See 'keys add'.
[!] Module 'recon/domains-hosts/shodan_hostname' disabled. Dependency required: ''shodan''.
[!] Module 'recon/hosts-ports/shodan_ip' disabled. Dependency required: ''shodan''.
[!] 'binaryedge_api' key not set. binaryedge module will likely fail at runtime. See 'keys add'.
[!] 'hashes_api' key not set. hashes_org module will likely fail at runtime. See 'keys add'.
[!] 'twitter_api' key not set. twitter_mentioned module will likely fail at runtime. See 'keys add'.
[!] 'twitter_secret' key not set. twitter_mentioned module will likely fail at runtime. See 'keys add'.
[!] 'twitter_api' key not set. twitter_mentions module will likely fail at runtime. See 'keys add'.
[!] 'twitter_secret' key not set. twitter_mentions module will likely fail at runtime. See 'keys add'.
[!] 'namechk_api' key not set. namechk module will likely fail at runtime. See 'keys add'.
[!] 'whoxy_api' key not set. whoxy_whois module will likely fail at runtime. See 'keys add'.
[!] Module 'recon/domains-companies/censys_companies' disabled. Dependency required: ''censys''.
[!] 'censysio_id' key not set. censysio module will likely fail at runtime. See 'keys add'.
[!] 'censysio_secret' key not set. censysio module will likely fail at runtime. See 'keys add'.
[!] 'github_api' key not set. github_dorks module will likely fail at runtime. See 'keys add'.
[!] 'virustotal_api' key not set. virustotal module will likely fail at runtime. See 'keys add'.
[!] Module 'recon/netblocks-hosts/censys_netblock' disabled. Dependency required: ''censys''.
[!] Module 'recon/netblocks-hosts/shodan_net' disabled. Dependency required: ''shodan''.
[!] 'bing_api' key not set. bing_linkedin_cache module will likely fail at runtime. See 'keys add'.
[!] Module 'recon/companies-contacts/censys_email_address' disabled. Dependency required: ''censys''.
[!] 'github_api' key not set. github_repos module will likely fail at runtime. See 'keys add'.
[!] 'google_api' key not set. reverse_geocode module will likely fail at runtime. See 'keys add'.
[!] 'google_api' key not set. geocode module will likely fail at runtime. See 'keys add'.
[!] 'twitter_api' key not set. twitter module will likely fail at runtime. See 'keys add'.
[!] 'twitter_secret' key not set. twitter module will likely fail at runtime. See 'keys add'.
[!] Module 'recon/locations-pushpins/shodan' disabled. Dependency required: ''shodan''.
[!] 'google_api' key not set. youtube module will likely fail at runtime. See 'keys add'.
[!] 'flickr_api' key not set. flickr module will likely fail at runtime. See 'keys add'.
[!] Module 'recon/ports-hosts/ssl_scan' disabled. Dependency required: ''M2Crypto''.
[!] Module 'recon/hosts-hosts/censys_ip' disabled. Dependency required: ''censys''.
[!] 'virustotal_api' key not set. virustotal module will likely fail at runtime. See 'keys add'.
[!] 'ipinfodb_api' key not set. ipinfodb module will likely fail at runtime. See 'keys add'.
[!] Module 'recon/hosts-hosts/censys_query' disabled. Dependency required: ''censys''.
[!] 'ipstack_api' key not set. ipstack module will likely fail at runtime. See 'keys add'.
[!] 'bing_api' key not set. bing_ip module will likely fail at runtime. See 'keys add'.
[!] Module 'recon/hosts-hosts/censys_hostname' disabled. Dependency required: ''censys''.
[!] 'github_api' key not set. github_miner module will likely fail at runtime. See 'keys add'.
[!] Module 'recon/companies-multi/shodan_org' disabled. Dependency required: ''shodan''.
[!] 'whoxy_api' key not set. whoxy_dns module will likely fail at runtime. See 'keys add'.
[!] Module 'recon/companies-domains/censys_subdomains' disabled. Dependency required: ''censys''.
[!] 'github_api' key not set. github_commits module will likely fail at runtime. See 'keys add'.
[!] Module 'recon/domains-contacts/metacrawler' disabled. Dependency required: ''PyPDF3''.
[!] 'hunter_io' key not set. hunter_io module will likely fail at runtime. See 'keys add'.
[!] 'pwnedlist_api' key not set. api_usage module will likely fail at runtime. See 'keys add'.
[!] 'pwnedlist_secret' key not set. api_usage module will likely fail at runtime. See 'keys add'.
[!] Module 'recon/domains-credentials/pwnedlist/domain_creds' disabled. Dependency required: ''pyaes''.
[!] Module 'recon/domains-credentials/pwnedlist/account_creds' disabled. Dependency required: ''pyaes''.
[!] 'pwnedlist_api' key not set. leaks_dump module will likely fail at runtime. See 'keys add'.
[!] 'pwnedlist_secret' key not set. leaks_dump module will likely fail at runtime. See 'keys add'.
[!] 'pwnedlist_api' key not set. domain_ispwned module will likely fail at runtime. See 'keys add'.
[!] 'pwnedlist_secret' key not set. domain_ispwned module will likely fail at runtime. See 'keys add'.
[!] 'fullcontact_api' key not set. fullcontact module will likely fail at runtime. See 'keys add'.
[!] Module 'recon/companies-hosts/censys_org' disabled. Dependency required: ''censys''.
[!] Module 'recon/companies-hosts/censys_tls_subjects' disabled. Dependency required: ''censys''.
[!] 'google_api' key not set. pushpin module will likely fail at runtime. See 'keys add'.
[recon-ng][default] > 
[recon-ng][default] > 
[recon-ng][default] > modules load recon/domains-hosts/hackertarget
[recon-ng][default][hackertarget] > info

      Name: HackerTarget Lookup
    Author: Michael Henriksen (@michenriksen)
   Version: 1.1

Description:
  Uses the HackerTarget.com API to find host names. Updates the 'hosts' table with the results.

Options:
  Name    Current Value  Required  Description
  ------  -------------  --------  -----------
  SOURCE  default        yes       source of input (see 'show info' for details)

Source Options:
  default        SELECT DISTINCT domain FROM domains WHERE domain IS NOT NULL
  <string>       string representing a single input
  <path>         path to a file containing a list of inputs
  query <sql>    database query returning one column of inputs

[recon-ng][default][hackertarget] > options set source tesla.com
[!] Invalid option name.
[recon-ng][default][hackertarget] > options set SOURCE tesla.com
SOURCE => tesla.com
[recon-ng][default][hackertarget] > run

---------
TESLA.COM
---------
[*] [host] tesla.com (199.66.11.62)
[*] [host] o7.ptr6980.tesla.com (149.72.144.42)
[*] [host] vpn1.tesla.com (8.45.124.215)
[*] [host] model3.tesla.com (205.234.27.221)
[*] [host] o3.ptr1444.tesla.com (149.72.152.236)
[*] [host] o2.ptr556.tesla.com (149.72.134.64)
[*] [host] o5.ptr8466.tesla.com (149.72.172.170)
[*] [host] o6.ptr9437.tesla.com (168.245.123.10)
[*] [host] o4.ptr1867.tesla.com (149.72.163.58)
[*] [host] mobile.tesla.com (209.133.79.82)
[*] [host] marketing.tesla.com (13.111.47.196)
[*] [host] referral.tesla.com (72.10.32.90)
[*] [host] mta2.email.tesla.com (13.111.4.231)
[*] [host] mta.email.tesla.com (13.111.14.190)
[*] [host] xmail.tesla.com (204.74.99.100)
[*] [host] comparison.tesla.com (64.125.183.133)
[*] [host] na-sso.tesla.com (199.66.9.46)
[*] [host] emails.tesla.com (13.111.18.27)
[*] [host] mta2.emails.tesla.com (13.111.88.1)
[*] [host] mta3.emails.tesla.com (13.111.88.2)
[*] [host] mta4.emails.tesla.com (13.111.88.52)
[*] [host] mta5.emails.tesla.com (13.111.88.53)
[*] [host] mta.emails.tesla.com (13.111.62.118)
[*] [host] click.emails.tesla.com (13.111.48.179)
[*] [host] view.emails.tesla.com (13.111.49.179)
[*] [host] events.tesla.com (13.111.47.195)
[*] [host] shop.eu.tesla.com (205.234.27.221)

-------
SUMMARY
-------
[*] 27 total (27 new) hosts found.
[recon-ng][default][hackertarget] > options set SOURCE iiitmk.in
SOURCE => iiitmk.in
[recon-ng][default][hackertarget] > run

---------
IIITMK.IN
---------
[*] [host] iiitmk.in (14.139.189.167)
[*] [host] emc.iiitmk.in (14.139.189.174)
[*] [host] geocod.iiitmk.in (14.139.189.166)
[*] [host] turn.iiitmk.in (182.76.52.102)
[*] [host] dev.iiitmk.in (14.139.189.174)
[*] [host] www.iiitmk.in (14.139.189.167)

-------
SUMMARY
-------
[*] 6 total (6 new) hosts found.
[recon-ng][default][hackertarget] >  



```