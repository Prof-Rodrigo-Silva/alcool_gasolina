# alcool_gasolina

<img src="https://img.shields.io/static/v1?label=version&message=v1.0&color=success&style=flat"/> <img src="https://img.shields.io/static/v1?label=build&message=passing&color=success&style=flat"/>
<a href="https://github.com/Prof-Rodrigo-Silva/alcool_gasolina/issues"><img alt="GitHub issues" src="https://img.shields.io/github/issues/Prof-Rodrigo-Silva/alcool_gasolina"></a>
<a href="https://github.com/Prof-Rodrigo-Silva/alcool_gasolina/network"><img alt="GitHub forks" src="https://img.shields.io/github/forks/Prof-Rodrigo-Silva/alcool_gasolina"></a>
<a href="https://github.com/Prof-Rodrigo-Silva/alcool_gasolina/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/Prof-Rodrigo-Silva/alcool_gasolina"></a>

**Project Status: Concluded** :heavy_check_mark:

## **Description**
Application compares the value of gasoline and alcohol and tells the user which is the best option to refuel.

Formula used:
```
if((precoAlcool/precoGasolina) >= 0.7){
        setState(() {
          _textoResultado = "Melhor abastecer com gasolina!";
        });
      }else{
        setState(() {
          _textoResultado = "Melhor abastecer com álcool!";
        });
      }
```

## **About Flutter**

Some resources for a Flutter project :hammer: :

- [Lab: write your first Flutter application] (https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Vibration Samples] (https://flutter.dev/docs/cookbook)

For help on starting Flutter, see the
[online documentation] (https://flutter.dev/docs), which offers tutorials,
samples, mobile development guidance, and a complete API reference.
