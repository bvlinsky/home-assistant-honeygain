ARG BUILD_FROM
FROM ${BUILD_FROM}

ENV token ""
ENV device-name ""

ENTRYPOINT ./Cli "start" "accept" "--token" "$token" "--device-name" "$device"
