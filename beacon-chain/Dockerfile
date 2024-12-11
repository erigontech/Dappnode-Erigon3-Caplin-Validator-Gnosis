FROM erigontech/erigon:main-f22317e


COPY entrypoint.sh /usr/local/bin/entrypoint.sh
COPY jwtsecret.hex /jwtsecret

EXPOSE $BEACON_API_PORT

#ENTRYPOINT while true; do echo "happy build $USERNAME!"; sleep 1; done
ENTRYPOINT ["sh", "/usr/local/bin/entrypoint.sh"]