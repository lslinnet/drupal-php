FROM wodby/php:5.3

    # Install drush
RUN su-exec www-data composer global require drush/drush:7.4.0 && \

    su-exec www-data composer clear-cache
