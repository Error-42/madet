# Aranymetszés

## Aranymetszés

Van két szakasz $a$, $b$ úgy, hogy $a<b$; melyekre igaz, hogy $\frac{a}{b}=\frac{b}{a+b}$. Ekkor az aranymetszés $\frac{a}{b}$[^1]. A $\frac{b}{a}$-t $\Phi$-vel jelöljük.

### Értéke:

$$\frac{a}{b}=\frac{b}{a+b}$$

$$a\left(a+b\right)=b^2$$

$$a^2+ab=b^2$$

$$a^2+ba-b^2=0$$

$$a_{1;2}=\frac{-b\pm\sqrt{b^2+4b^2}}{2}=b\cdot\frac{-1\pm\sqrt5}{2}$$

$$a_1=b\cdot\frac{-1-\sqrt5}{2}<0\;\text{↯}$$

$$a_2=b\cdot\frac{-1+\sqrt5}{2} \Rightarrow \frac{a_2}{b}=\frac{\sqrt5-1}{2}\approx0,618$$

### Szerkesztése

![](imgs/aranymetsz%C3%A9s-szerkeszt%C3%A9se.png)

1. Vegyünk fel egy $r=\frac{a}{2}$ sugarú $O$ középpontú $k$ kört, rajta egy $E$ pontot.
2. Szerkesszünk egy $a$ hosszú a kört érintő $PE$ szakaszt.
3. $A$ legyen $PO \cap k$.

Ekkor $\frac{PE}{PA}=\Phi$.

#### 1. bizonyítás

Pitagorasz-tétel $EPO_\Delta$-ban:

$$EP^2+EO^2=\left(PA+AO\right)^2$$

$$PA=\sqrt{EP^2+EO^2}-AO=\sqrt{a^2+\left(\frac{a}{2}\right)^2}-\frac{a}{2}=a\cdot\frac{\sqrt5-1}{2}=PE\cdot\frac{\sqrt5-1}{2}$$


#### 2. bizonyítás

$B$ legyen a $PO$ és $k$ másik metszéspontja.

[Érintő és szelő szakaszok tétele](../körök/érintő-és-szelő-szakaszok-tétele.md) szerint:

$$PE = PA \cdot PB$$

$$a = PA \left(PA + 2r \right)$$

$$a = PA^2 + 2r \cdot PA$$

$$PA^2 + 2r \cdot PA - a = 0$$

todo: befejezni

## 72°; 72°; 36° háromszög

A szárak és az alap hányadosa $\Phi$.

### 

[^1]: Bizonyos leírásokban $\frac{b}{a}$.
