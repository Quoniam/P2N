     _____      _             _     ___    _   _      _           _____   ___    _   _ 
    |  __ \    | |           | |   |__ \  | \ | |    | |      /  |  __ \ |__ \  | \ | | \
    | |__) |_ _| |_ ___ _ __ | |_     ) | |  \| | ___| |_    /   | |__) |   ) | |  \| |  \
    |  ___/ _` | __/ _ \ '_ \| __|   / /  | . ` |/ _ \ __|   |   |  ___/   / /  | . ` |   |
    | |  | (_| | ||  __/ | | | |_   / /_  | |\  |  __/ |_     \  | |      / /_  | |\  |  /
    |_|   \__,_|\__\___|_| |_|\__| |____| |_| \_|\___|\__|     \ |_|     |____| |_| \_| /       
About
-----
Patent2Net is :
* elaborated and maintained (on a free base) by a small international team of professors and researchers.  
* an "open source" package and contributions are welcome
* available "as it is".

Patent2Net is a free package, dedicated to :
* augment the use of patent information in academic, nano and small firms, developing countries (all those without pay mode access)
* learn, study and practice how to collect, treat and communicate "textual bibliographic information", and automation process
* provide statistical analysis and representations of a set of patents.

The [results](http://patent2netv2.vlab4u.info/) of statistical patents analysis can be explored as a website with the firefox browser
--------------------------------------------------------------------------------
A [binary version] (http://patent2netv2.vlab4u.info/dokuwiki/doku.php?id=user_manual:download_install;) is available
--------------------------------------------------------------------------------------------------------------------
[Train how to search patent information using interface] (http://patent2netv2.vlab4u.info/dokuwiki/doku.php?id=user_manual:patent_search;)
------------------------------------------------------
Install Patent2Net python scripts on Windows
--------------------------------------------
To run as python script, see the file install-dev.txt
Install Patent2Net on Linux (Fix needed).
---------------------------
See requirements.txt and InstallP2NLinux.txt
If you're using Ubuntu or Debian distributions, make sure to have PIP installed:

    sudo apt-get install python-pip build-essential python-dev libjpeg-dev libxml2-dev libfreetype6-dev libpng-dev

Then, run the requirements.txt file to install all dependencies:

    sudo pip install -r Development/requirements.txt

To use the current Development version, you can make a symbolic link to your desired folder:

    ln -sd Development Patent2Net

Use Patent2Net (script mode)
----------------------------
Follow the "To register and use the CRAWLER:" [described here] (http://patent2netv2.vlab4u.info/dokuwiki/doku.php?id=user_manual:download_install;) to install your acreditation in the “cles-epo.txt” file in root directory.

Copy any of the *.cql file from /RequestsSets directory as requete.cql in root directory, and/or adapt the requete.cql to your need.

Use the /Patent2Net/ProcessPy.bat and enjoy!

Further insformation:
---------------------
In our [documentation page] (http://patent2netv2.vlab4u.info/dokuwiki/doku.php;)

Todo List (not limitative, just ideas):
---------------------------------------
#### Although Patent2Net works fine and is enough to begin using Patent Information, a lot can be done to improve analysis:
* Correct the issues (of course)
* Add some more information in the result html page (ModeleContenuIndex.html). Great to add the treating date (thus can be different from gathering) and P2N version
* Improve the Mindmap option to get it more efficient for creativity (Celso is working on)
* Build the entire network as a gephi file for download to let new combined network analysis possible

#### Add some new capabilities to Patent2Net, i.e.:
* Within the Patent Universe, build a drawings gallery with hyperlink to the Espacenet patent full text (Andre is thinking about)
* Build a small database to display results of a specific (Familly) Patent Universe. Database could be [PouchDB] (https://pouchdb.com/) or equivalent
* Within the Familly Patent Universe, provide all the same analysis as with the Patent Universe

#### Provide some new ways of gathering and anlysis of patent information, i.e.:
* Within the Familly Patent Universe, provide a new range of analysis, considering a familly as a unique entity (invention)
* Limit the Familly Patent Universe to the only Priority patents, and provide a complete analysis
* Using citations of the Familly Patent Universe, provide genealogic analysis, especially descendants to try to detect invention fronts.

#### New contributions and ideas are welcome

