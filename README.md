# wooltube-education
WOOLtubeのyoutubeeducationのみを使った形式です。

検索にはyoutube公式APIを使っています。

使いたいAPIを自分で選んでください。

１日１００回ずつなので使えなければ他の物に変えてください。

educationのパラメーター・keyは[ここ](https://raw.githubusercontent.com/woolisbest-4520/about-youtube/refs/heads/main/parameter.json)から自動で取得しています。

埋め込みの形式は
```
https://youtubeeducation.com/embed/{動画ID}{パラメーター・key｝
```
パラメーターの形式は
```
{
  "key":"?
autoplay=1
&mute=0
&controls=1
&start=0
&end=20
&origin=https%3A%2F%2Fkahoot.it
&playsinline=0
&showinfo=0
&rel=0
&iv_load_policy=3
&modestbranding=1
&fs=1
&cc_load_policy=1
&embed_config=%7B%22enc%22%3A%22
```
⬇️これがkeyです。　２日ごとに更新されます⬇️
```
AXH1ezkiXo17vRFSmeJwtJuHR_dDGUGjPpAznRqtn2I41n3nIoDnfF4V6wGHAAKkCmAqKygzEypC7-MwGP8y3ZuIGAXVi8Am0zFkaTI_87rIulYXsBTnv-el9SHDLk86ZP8kMI0GKlSlAXazdpXB29jSjlx5eLDQq
```
⬆️key⬆️
```
A%3D%3D%22%2C%22hideTitle%22%3Atrue%7D
&enablejsapi=1
&widgetid=1
&forigin=https%3A%2F%2Fkahoot.it%2Fsolo%2F%3FquizId%3Dc351231f-5db9-436f-aca0-77ef7fa2b7ba&aoriginsup=1
&gporigin=https%3A%2F%2Fkahoot.it%2Fsolo%2Foauth2%2Fauthenticated%3Fcode%3D1eN4iEa8R1tsjzUsQwn286hdx6K_SJ_BtT7OQxxkFZ0%26state%3D24d1e50fc9da4baeb5de306c2da25d57
&vf=6"
}
```
こうなっています。
