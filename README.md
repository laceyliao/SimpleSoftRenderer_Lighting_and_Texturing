# SimpleSoftRenderer_Lighting_and_Texturing

## using Bilinear interpolation of texture
$$
\begin{aligned}
& \text{lerp}(k,v0,v1)=v0+k(v1-v0);\\
&u0 = \text{lerp}(s,u00,u10);\\
&u1=\text{lerp}(s,u01,u11);\\
&f(x,y)=\text{lerp}(t,u0,u1);
\end{aligned}
$$

## Point Light(Blinn-phong shading)
<img src="images/blinn_phong.gif" width=70%>

## Spot Light
<img src="images/spolight2.gif" width=70%>

## Acknowledgements
The framework is derived from ZeusYang's [TinySoftRenderer](https://github.com/ZeusYang/TinySoftRenderer/tree/master).
