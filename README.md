# debian-wkhtmltopdf

Simple image with the latest **wkhtmltopdf** installed on a nice and stable Debian **slim**, which today is **stretch**. Different of my other repo, this one will be update as frequent as a new Debian release gets supported by wkhtmltopdf. At least that's the idea.

    git clone https://github.com/leandrosilva/debian-wkhtmltopdf.git
    cd debian-wkhtmltopdf
    docker build -f Dockerfile -t debian-wkhtmltopdf .
    docker run -it -v /whatever/path/you/like/:/whatever --name debian_wk debian-wkhtmltopdf
    wkhtmltopdf http://www.google.com google_home.pdf

Boom! There you go...
