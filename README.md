# MQTT Antena Home Assistant Add-on
[![Open your Home Assistant instance and show the add add-on repository dialog with a specific repository URL pre-filled.](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Fhome-assistant%2Faddons-example)

This directory contains the files to run MQTT Antena as a Home Assistant add-on.

## About

MQTT Antena is a simple, modern, web-based MQTT client application that allows you to manage broker connections, monitor message streams, and publish messages through a clean web interface.

## Installation (as a local add-on)

1.  Copy the `addon/` directory from this repository into your Home Assistant `addons/` directory.
2.  In Home Assistant, navigate to `Settings -> Add-ons -> Add-on Store`.
3.  Click the three dots in the top right and select "Check for updates".
4.  Your add-on should appear under the "Local add-ons" section.
5.  Install the "MQTT Antena" add-on.
6.  Configure the `secret_key` in the Configuration tab. This is a mandatory field.
7.  Start the add-on.
