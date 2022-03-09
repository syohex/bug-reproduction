FROM debian:11
RUN apt-get -y update
RUN apt-get -y --no-install-recommends install perl make cpanminus
RUN apt-get -y --no-install-recommends install libclass-accessor-lite-perl libencode-perl libhttp-parser-xs-perl
RUN apt-get -y --no-install-recommends install libtest-tcp-perl
ENV LOCALDOMAIN bing.com
CMD cpanm --test-only --verbose Furl
