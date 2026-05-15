# Huong dan cap nhat quang cao

Quang cao chi hien thi bang anh hoac video trong hai cot ben trai/ben phai khi xoay ngang. App khong gan link va khong mo web khi hoc sinh cham nham.

## Cach lam

1. Upload file anh/video vao thu muc `ads`.
2. Sua file `ads.json`.
3. Upload lai len GitHub Pages.

Vi du:

```json
{
  "schemaVersion": 1,
  "durationSeconds": 12,
  "left": [
    {"src": "ads/quang-cao-1.jpg", "type": "image", "alt": "Quang cao 1"},
    {"src": "ads/quang-cao-2.mp4", "type": "video", "alt": "Quang cao 2"}
  ],
  "right": [
    {"src": "ads/quang-cao-3.jpg", "type": "image", "alt": "Quang cao 3"}
  ]
}
```

Neu chi muon dung chung mot danh sach cho ca hai ben:

```json
{
  "schemaVersion": 1,
  "durationSeconds": 12,
  "items": [
    {"src": "ads/quang-cao-1.jpg", "type": "image"},
    {"src": "ads/quang-cao-2.mp4", "type": "video"}
  ]
}
```

Nen dung anh ngang/doc don gian, chu to, it chi tiet. Video nen ngan, nhe, khong co am thanh.
