![ml-model-diagram](https://github.com/C23-PS317/ml-model-deployment/assets/69651946/1978a426-cc45-4841-8b95-6e42cfb831f1)

# ML Model Deployment

## Endpoint

- base url: https://ml-model-deployment-ymrdyfncwq-et.a.run.app/

- Path : `/predict/{userId}`
- Method : `POST`
- Request Body (form-data) :
  - file as `image`, jpg format
- Response :

```json
{
    "nama": "air",
    "kalori": 0,
    "satuan": "ml",
    "image_db": "https://storage.googleapis.com/foods-image/foods/air_train%20(6).jpg",
    "image_user": "https://storage.googleapis.com/foods-image/41OD8U1Tn0N3GC2VMkVH5HnFf2r2/air_train%20%282%29.jpg"
}
```
