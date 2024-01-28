# DockerProject
# Практическое задание от Skillbox Mod5

#! /bin/bash

timet="`date "+%d.%m.%Y %H:%M:"`"

for ((i=0; i<5; i++))
do
sleep 1; echo $timet`date +%S`
done
