# reverse-rdssh-actions

## Screenshot


### RDP, VNC
<details>
<summary>ubuntu</summary>

![ubuntu-rdp](https://user-images.githubusercontent.com/50764666/122870143-40135380-d368-11eb-9d69-79b2e360bfdf.png)

</details>

<details>
<summary>windows</summary>


![windows-rdp](https://user-images.githubusercontent.com/50764666/120478488-dd254100-c3e7-11eb-9fb9-5afa2ac7e44f.jpg)

</details>

<details>
<summary>macos (vnc)</summary>

![macos-vnc](https://user-images.githubusercontent.com/50764666/122869654-8caa5f00-d367-11eb-9511-3c75f7f51527.png)

</details>

### SSH

<details>
<summary>ubuntu</summary>

![ubuntu-ssh](https://user-images.githubusercontent.com/50764666/122866889-ac3f8880-d363-11eb-9e2f-b0c271a83083.png)

</details>

<details>
<summary>macos</summary>

![macos-ssh](https://user-images.githubusercontent.com/50764666/122867651-caf24f00-d364-11eb-95e6-2b9dfd9e2e16.png)

</details>

## Usage
1. Download [cloudflared](https://github.com/cloudflare/cloudflared/releases/latest) to your computer.
2. Under the repository's settings, make a secrets called `PASSWORD`
3. Trigger a workflow in actions page.
4. Open terminal on your computer and run this command:\
    `CLOUDFLARED_FILE_NAME access tcp --url localhost:PORTFROMLOCAL --hostname URL_FROM_ACTIONS_LOG`
5. Done!

## Info
- Please use this for debugging~
- [Runners can run jobs for up to 6 hours](https://docs.github.com/en/actions/reference/usage-limits-billing-and-administration#usage-limits)

---

## License
See: https://ksp.mit-license.org