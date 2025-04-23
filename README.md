# CAN Bus API

Simple server that takes your CAN bus data (provided you have a valid key), and saves it on a centralized server.

## Application

You install a Raspberry Pi in your car that taps into the CAN bus stream. The Raspberry Pi records that data and dumps into its own storage, then, when you're home. It sends those logs to the server as soon as it connects to your network.

## Why?

This is a (small) step in the process of reverse engineering my CAN bus data so I can remotely control my car (Ignition, AC, Heating, etc.)
