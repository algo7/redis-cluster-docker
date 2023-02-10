# Set the baseImage to be used
FROM redis:alpine

# Copy the redis.conf
COPY redis.conf /etc/redis.conf

#  Command to execute at the end, each parameters in an element in the array
CMD [ "redis-server", "/etc/redis.conf"]

EXPOSE 7000

