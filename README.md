var source = Marzipano.ImageUrlSource.fromString(
  "data/tiles/{z}/{f}/{y}/{x}.jpg",
  { cubeMapPreviewUrl: "data/preview.jpg" } // ✅ 프리뷰 이미지 추가
);
