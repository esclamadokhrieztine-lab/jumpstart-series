Name: Esclamado, Khrieztine L.
ID: 2024300636

Name: Sabuero, Zyra Faith A.
ID: 2024300673

Branch: student-Esclamado


Notes: 
    Sa pag npm run dev diay sir kay di sya ga work tong una, sooo ang ginawa namin ayyy... nag ask mi ni Claud ai about the problem. 
    And mao ni amo gi buhat: 

        Cloned the repo, checked out quick-demo branch, created .env.local with your MONGODB_URI (password filled in).
        Ran npm install — succeeded (ignored the audit warnings, they're normal for this old repo).
        Hit a Node v24 / OpenSSL error on npm run dev (digital envelope routines::unsupported) — classic newer-Node vs older-webpack issue.
        Fixed it permanently by installing cross-env and changing the dev script in package.json to:
            json
                "dev": "cross-env NODE_OPTIONS=--openssl-legacy-provider next dev"
        Confirmed localhost:3000 loads the product list.
        Then makita na dayun namo siya. THE END


    PS. Very hago man diay sya sirr. Maoy naka cause ug lag sa ako lappy HHAHAHAHAH, pero na keri ra. Lumalaban lang Alaxan!
