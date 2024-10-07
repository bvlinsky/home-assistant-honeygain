FROM iproyal/pawns-cli:0.33.0

ENV email ""
ENV password ""
ENV device "HomeAssistant"
ENV deviceId "homeassistant"

ENTRYPOINT /pawns-cli "-accept-tos" "-email=$email" "-password=$password" "-device=$device" "-device-id=$deviceId"
