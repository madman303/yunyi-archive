---
layout: page
title: 双人 · 日常直播
subtitle: 云熠双人直播回放合集
---

<style>
  /* 两栏布局 */
  .two-columns {
    display: flex;
    gap: 2rem;
    flex-wrap: wrap;
  }
  .left {
    flex: 2;
    min-width: 250px;
  }
  .right {
    flex: 1;
    min-width: 180px;
    background: #f8fafc;
    border-radius: 24px;
    padding: 1.2rem;
    align-self: start;
    box-shadow: 0 2px 8px rgba(0,0,0,0.05);
  }

  /* 视频卡片样式 */
  .video-list {
    display: flex;
    flex-direction: column;
    gap: 1rem;
  }
  .video-item {
    background: #fff;
    padding: 1rem;
    border-radius: 16px;
    border-left: 4px solid #0d9488;
    box-shadow: 0 1px 3px rgba(0,0,0,0.05);
  }
  .video-item a {
    font-weight: bold;
    text-decoration: none;
    color: #0d9488;
  }
  .date {
    color: #64748b;
    font-size: 0.85rem;
    margin-bottom: 0.25rem;
  }

  /* 右侧图片框 */
  .photo-box {
    text-align: center;
  }
  .photo-box img {
    width: 100%;
    border-radius: 20px;
    margin-bottom: 1rem;
    box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  }
  .photo-caption {
    font-size: 0.85rem;
    color: #64748b;
    margin-top: 0.5rem;
  }

  /* 青色圆角按钮 */
  .btn-teal {
    display: inline-block;
    background: #0d9488;
    color: white;
    padding: 10px 20px;
    border-radius: 40px;
    text-decoration: none;
    font-weight: bold;
    text-align: center;
    transition: background 0.2s;
    margin-top: 1rem;
    width: 100%;
    box-sizing: border-box;
  }
  .btn-teal:hover {
    background: #0f766e;
  }
</style>

<div class="two-columns">
  <!-- 左侧：直播视频列表 -->
  <div class="left">
    <div class="video-list">
      <div class="video-item">
        <div class="date">2025-05-01</div>
        <a href="https://www.alipan.com/s/h7EM7Yt3Kh3" target="_blank">🎥 云熠第一次正式双人直播</a>
        <p>两人分享拍摄趣事，甜度超标。</p>
      </div>
      <!-- 可以继续添加更多 .video-item -->
    </div>
    > ⭐ 首次访问需登录阿里云盘，之后可直接播放。
  </div>

  <!-- 右侧：图片 + 青色按钮 -->
  <div class="right">
    <div class="photo-box">
      <img src="/yunyi-archive/assets/img/cp-live/25-12-1.jpg" alt="直播甜蜜瞬间">
      <div class="photo-caption">✨ 云熠直播甜蜜瞬间</div>
      <a href="https://www.alipan.com/s/你的直播合集链接" class="btn-teal" target="_blank">
        📸 更多直播花絮
      </a>
    </div>
  </div>
</div>
