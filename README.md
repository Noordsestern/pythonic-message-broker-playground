# About

A playground trying out several message broker variants for Python.

It seems hard to find a pythonic message broker that does not required a 3rd-party installation like RabbitMQ or Redis. Unfortunately, dedicated message broker are so popular and common, python packages like Kombu or Celery do not particular state if they only provide the interface to a message broker if they actually work without need of a dedicated broker.

In this playground, I try out a few solutions that seem to run with `pip install` only. Maybe.