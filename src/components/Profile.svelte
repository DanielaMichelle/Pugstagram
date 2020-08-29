<script>
import { SSL_OP_MICROSOFT_BIG_SSLV3_BUFFER } from "constants";

export let nickname
export let name

</script>
<div class="Profile">
    <div class="Profile-content">
        <div class="Profile-avatar">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcTRCtf5JDYu-MkbLeD9OnP1LEZcTNfIkJUsmg&usqp=CAU" alt="User">
        </div>
        <div class="Profile-info">
            <h2>{nickname}</h2>
            <span>{name}</span>
        </div>
    </div>
</div>

<style>
    .Profile-content {
      display: flex;
      align-items: center;
    }
    .Profile-avatar img {
      width: 40px;
      height: 40px;
      border-radius: 50%;
    }
    .Profile-info {
      margin: 0 0 0 0.5em;
    }
    .Profile-info h2 {
      font-size: 14px;
      color: black;
      margin: 0;
      padding: 0;
    }
    .Profile-info span {
      font-size: 12px;
      font-weight: normal;
    }
  </style>