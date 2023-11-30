# Dicas para Deploy

## Upload de arquivos grandes

use `git lfs` para subir arquivos grandes maiores que 10MB:
+ Execute `git lfs install` no repositório
+ Adicione os arquivos e extensões grandes

````sh
git lfs track "09_pretrained_effnetb2_feature_extractor_pizza_steak_sushi_20_percent.pth"
git lfs track "09_pretrained_effnetb2_feature_extractor_food101_20_percent.pth"
git lfs track "*.psd"
````

+ Faça isso antes de dar o `git add`

## Push no hugging face

Utilize acesso ssh, ele já é conectado ao computador, assim, não precisa inserir senha



