version: '3.8'

services:
  hibob-web:
    build: .
    container_name: hibob-web
    restart: unless-stopped
    networks:
      - openclaw_default

networks:
  openclaw_default:
    external: true
