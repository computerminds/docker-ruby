FROM ruby:1.9.3

MAINTAINER Steven Jones <steven.jones@computerminds.co.uk>

ADD Gemfile /tmp/Gemfile
ADD Gemfile.lock /tmp/Gemfile.lock

WORKDIR /tmp

RUN bundle
