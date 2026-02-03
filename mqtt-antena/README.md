# MQTT Antena Home Assistant Add-on

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
