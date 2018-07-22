docker build -t python_gpio_alp .
docker run --privileged -p 8080:8080 -it python_gpio_alp bash