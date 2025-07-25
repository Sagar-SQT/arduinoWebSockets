idf_component_register(
    SRCS "src/WebSockets.cpp" "src/WebSocketsClient.cpp" "src/WebSocketsServer.cpp"
    INCLUDE_DIRS "src"
    REQUIRES espressif__arduino-esp32
)