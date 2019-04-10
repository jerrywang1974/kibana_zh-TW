# kibana_zh-TW

# Environment and tested on 6.7.1 version of kibana

Procedure:

1. modify kibana.yml and adding i18n property
   # vi /etc/kibana/kibana.yml
    adding => i18n.locale: "zh-TW"
2. copy zh-TW.json to folder
   # cp zh-TW.json /usr/share/kibana/node_modules/x-pack/plugins/translations/translations/zh-TW.json
3. Restart kibana service
   # systemctl restart kibana
4. done



