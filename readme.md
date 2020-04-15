### Custom themes cho videos player

Fork từ phiên bản videojs 7.3.0

Dự án này chỉ can thiệp css của videojs tránh dùng themes mặc định nhàm chán

#### Khai báo

sau khi clone về bạn thêm 2 dòng dưới đây vào trong cặp thẻ `<head></head>`

```
<link href="<đường dẫn tới>/video.css" rel="stylesheet">
<script src="<đường dẫn tới>/video.min.js"></script>
```

#### Sử dụng

Chèn đoạn code nhúng player vào trang bên trong `<body>`

```
<video
    id="my-player"
    class="video-js"
    controls
    preload="auto"
    poster="//vjs.zencdn.net/v/oceans.png"
    data-setup='{}'>
  <source src="//vjs.zencdn.net/v/oceans.mp4" type="video/mp4"></source>
  <p class="vjs-no-js">
    To view this video please enable JavaScript, and consider upgrading to a
    web browser that
    <a href="https://videojs.com/html5-video-support/" target="_blank">
      supports HTML5 video
    </a>
  </p>
</video>
```

Mọi cài đặt js theo guides của videojs

Nguồn & hướng dẫn chi tiết: https://github.com/videojs/video.js

Hình ảnh demo themes

<!--gold start-->
<table>
  <tbody>
    <tr>
      <td align="center" valign="middle">
        <a href="https://raw.githubusercontent.com/codego-vn/player.js/master/img/playing.png" target="_blank">
          <img width="350px" src="https://raw.githubusercontent.com/codego-vn/player.js/master/img/playing.png">
        </a>
      </td>
      <td align="center" valign="middle">
        <a href="https://raw.githubusercontent.com/codego-vn/player.js/master/img/thumb.png" target="_blank">
          <img width="350px" src="https://raw.githubusercontent.com/codego-vn/player.js/master/img/thumb.png">
        </a>
      </td>
    </tr>
  </tbody>
</table>
<!--gold end-->