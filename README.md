# Seran Outpost Reader

We basically scraped the HTML from a seran wiki and fiddled until it
would work as a simple website.

Try it yourself:

    git clone this over-there
    cd over-there
    docker run -d --rm -p2015:2015 -v"$PWD:/it" -w /it dobbs/proxy caddy browse
    open http://localhost:2015
