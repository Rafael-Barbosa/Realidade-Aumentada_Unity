# Realidade Aumentada Unity

### Aplicação Simples de Realidade Aumentada Unity + Vuforia

<p  align="justify"> Unity e Vuforia fornecem uma solução poderosa para o desenvolvimento de aplicativos de AR, permitindo que os desenvolvedores criem experiências de AR incríveis para uma ampla gama de aplicações.
</p>

<p  align="center">
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">             
<br>


<p align="center">
<img src="Img/vuforia.png" width="460" height="300">
</p>

<!--GIF-->
<p align="center">
<img src="Img/Gif_1.gif" width="460" height="300">
</p>

#### Para fazer uma aplicação como esta acima basta fazer o download do Vuforia Engine:

>  O Vuforia Engine pode ser facilmente importado para o Unity

[Download Vuforia](https://developer.vuforia.com/user/login?url=/downloads/sdk%3F_%3D1678117884)


>  É necessário criar uma conta e uma licença para registrar o seu Target (alvo).
> Após isso faça o Download do seus banco de dados (target+features).

<!--Target-->
<p align="center">
<img src="Img/Target.png">
</p>


<!--Target-->
<p align="center">
<img src="Img/targetmod.png">
</p>

> A Figura acima mostra o mapeamento para realidade aumentada.

#### Monte sua cena:

> Incluindo o Imagem Target e a Câmera AR

<!--Unity-1-->
<p align="center">
<img src="Img/unity-1.png">
</p>

#### O script para rotacionar o Cubo

```javascript
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class rotate : MonoBehaviour
{
    public Vector3 rotateAmount;
    void Start()
    {
        
    }

    void Update()
    {
        transform.Rotate(rotateAmount * Time.deltaTime);
    }
}
```

#### Basta escolher o eixo de rotação e a módulo da posição nesse caso:
> X = 50, Y = 50, Z = 50.

<!--Detalhes-1-->
<p align="center">
<img src="Img/Detalhes.png">
</p>

> O Unity é uma plataforma de desenvolvimento de jogos que também pode ser utilizada para desenvolver aplicativos de AR.

## Contribua :)

1 - Fork it

2 - Cria sua feature branch (git checkout -b my-new-feature)

3 - Commit suas mudanças (git commit -am "Added some feature")

4 - Push na sua branch (git push origin my-new-feature)

5 - Crie novo Pull Request
