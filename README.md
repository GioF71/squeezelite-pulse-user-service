# squeezelite-pulse-user-service

Run squeezelite over pulseaudio with systemd at user level.
It uses PulseAudio as output device using the name "squeezelite-pulse".

## Prerequisites

- You will need to have SqueezeLite installed.

## Install/Remove  

Install by simply running

`sh install.sh`

You can remote the service running

`sh remove-service.sh`

## Usage

### Start, Stop and Restart

The service can be managed with the usual systemd commands.

#### Start squeezelite-pulse

`systemctl --user start squeezelite-pulse`

#### Stop squeezelite-pulse

`systemctl --user stop squeezelite-pulse`

#### Restart squeezelite-pulse

`systemctl --user restart squeezelite-pulse`

Equivalent convenience scripts are also provided (start.sh, stop.sh, restart.sh).
