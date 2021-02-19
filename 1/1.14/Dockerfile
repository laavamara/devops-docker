FROM ruby:2.6.0
RUN curl -sL https://deb.nodesource.com/setup_10.x | bash
RUN apt install -y nodejs
COPY . .
RUN gem install bundler
EXPOSE 3000
RUN bundle install
RUN rails db:migrate
CMD rails s
