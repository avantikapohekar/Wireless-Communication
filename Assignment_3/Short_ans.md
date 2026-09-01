# 1. Explain Reflection, Diffraction and Scattering mechanisms of radio propagation.

## Reflection, Diffraction and Scattering in Wireless Communication

In wireless communication, **reflection, diffraction, and scattering** are the three major mechanisms that affect the propagation of electromagnetic (radio) waves. They determine the different paths followed by a signal from the **transmitter (Tx)** to the **receiver (Rx)**.

Because a signal can reach the receiver through several different paths, these mechanisms are major causes of **multipath propagation**, which can result in fading, interference, and signal distortion.

---

### 1. Reflection

![Image](https://images.openai.com/static-rsc-4/ufiTTYx1kVqGXHiXM4KW-wKFPPWOM_pzYoBdxFRhJSVmjNzsRkrdo7Tgt-_FzklcdTJCFsEukulSWiagyH1v8OsiXV-Ye2TxPRoogVolMR4ZX-ULpXhQQ0IGe6RvpNAyBObcjgOFJjKqq0u22EuQGitp0EachkD8R1HHskTa1FVmyTd16HQq2zryqC3ZJJTr?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/I0-qR35HveBJZXW8SZ10GtozWcnxPSQ4_jrFSKAhov1m0RDo8UfQ6uzURWfFvxeh3Mi2OMoInozzZBlIOI1rGHFR8LYSzde176sFUPayF488KYpnJuNKbWkzKKplMNdlK4YEhC9Ettj_U3UxMrPdoLolWzUlxuzungzNSFK3q6FcirPFBIVNzw_JxtzX9hUR?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/ZYqPq9FMI7Kz_Zpv6VsFHRYYTj7u3Mt-fLr50q8QV9z5ba2D7cmklq12YGxya_HDlFupe-tyVIaGQBBmibnkXvW7dk4--zqE6FXgBeSZ1HTSvILAp-GOcKoscrFxDeL486MNmoCRYIyLuOLWtyKFphsLsgh4m8YS8mMCMCsl7rubji_KTVObYOWwlSQNmxZl?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/5ctOr6uKS97xH-27hpiisogsSJAf20ak9C3pVk2NtSCdXVVXyR8dD_5AAKxlaVCwohMZQzJd3jz5TEbn9moVuBeLmzSZC6fpyC-9pblbeHDP8Te0US2xQ4Re36X2XrKoUyhw4tYiHx9IudzOmDqjx5vnZIPGP1p2IcDSarjEpYjO0fxd0kKEktj_HcXyZayM?purpose=fullsize)

**Reflection** occurs when a radio wave strikes a **large, smooth surface** whose dimensions are much larger than the wavelength.

The wave **bounces off the surface** and travels toward the receiver through a different path.

**Examples:**

* Buildings
* Concrete walls
* Roads
* Earth's surface
* Large metal objects
* Water surfaces

**Effect:** Reflection produces additional signal paths. These reflected signals may combine constructively or destructively with the direct signal, causing **multipath fading**.

**Example:** A cellular signal may bounce off a large building before reaching a mobile phone.

---

### 2. Diffraction

![Image](https://images.openai.com/static-rsc-4/1Faqd1pRYFYYssd6qOJj3X3p5bbsGGXqpFnjb8vtobYol5floMT_DT6ZOw70BEy7bxFoosH0GK5ILrTObQ-wKsPRgxcktuvS7FMtDDp9OPjV7HGhuMTij7QVohrbThDqsCwHpEVc_CJoPpENFkQL9ft9DWzvIJe1H2xmxxrSDK9rbleePYZRL_5swJrXrDJu?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/NyKcRJoFC3huQ9cAmRUz44BvUYlxdYgBM05rdSaOcLfYGbrk4F8Hy9Wod5f_ZfId44md9ZpkOQV712Ig4j2ayyonhB3ojJ-MaGb0_Apy0DkB9NILO6PsR1yigFfVwqyNiWFSncCGS3j8BRnRBnFcsjrcfsgfo6mPEdGmdo61TEERlYJhmZk7EeygajM_vgpp?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/NmP_wZcerBRTVy6LRh22wZkj7wgcC2lyNYeqVNQNajjJtsEgEGzKIVW2GvJSg5juc4XIoCma4fdXGIfYPfAcHB6eJEVRWHw2LlO5MXMbRpmVeSjnPn5y0hwCtRvFUgPGf-4aw9JR4bI8udzpCvdMaMMPebFz8zXkwDKbXxHOLa8h7JI35KAVyTZZOhXiyuE9?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/5ctOr6uKS97xH-27hpiisogsSJAf20ak9C3pVk2NtSCdXVVXyR8dD_5AAKxlaVCwohMZQzJd3jz5TEbn9moVuBeLmzSZC6fpyC-9pblbeHDP8Te0US2xQ4Re36X2XrKoUyhw4tYiHx9IudzOmDqjx5vnZIPGP1p2IcDSarjEpYjO0fxd0kKEktj_HcXyZayM?purpose=fullsize)

**Diffraction** occurs when a radio wave encounters an **obstacle or sharp edge** and bends/spreads into the region behind the obstacle.

It is especially important for **Non-Line-of-Sight (NLOS)** communication.

**Examples:**

* Buildings
* Hills
* Mountains
* Large walls
* Large rocks

**Effect:** Diffraction allows a signal to reach areas that are not directly visible from the transmitter. However, the signal reaching the shadow region is generally weaker.

**Example:** A mobile phone can sometimes receive a signal even when a building blocks the direct path from the base station.

---

### 3. Scattering

![Image](https://images.openai.com/static-rsc-4/e71wFT-KZsLHQ4SLFv5jJowX-ci6PFRmQndInS2Wh53PrDB7Biux9tZJTE8pHGmoP78KQgvs81_M4i1DgPRu9inJGiMoHvcSNeDZhZ8z48wLG2tgQvKnIhV7RsOsztHrGHESlO2VihXWQkeu1F3ffVKTOFyvsfSCr6lZqUhxkr97e7GWM0IwPjOLx_3e_4uZ?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/xyQJQYn884OlWBxjRebMhboDDUdla5hvusTKqmcXled1j1gbc2gQAUuD5yTB272HgDaiRlUV1Aen_KZgjBE_OQ09egUcUMnxvu1R-X28LSnIJt6YTdgxnw-L9psO899t39TF_ASK5DlhF3-fd0aTrU5vTYhvYmSGkv7E8NN_MxkuS1ftqD4tUtOSeJKqOyAq?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/EgMQmnlxusaZcIQCdOvOI7oIA1iIhVsKN5pC2WzH5poWdi0KAmH26ANKUOFhCJ8yFC6Mver8GHSobLvkDwsYDR9IfYZ2yb8bVGAXFYb5puA9S4MLyCgui0Ig3igQcEwmPzS0YXMkYY1Iv7twgS25AsTjYFBBfnq8651Oy9gaBEHg6nldhu0hAOAosCGrhPkn?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/qytxtRLt52vAK-w5QJTW5wtss8WZ3iOyTtTpVNKlqJXoO8RkHT5HfXR-z8CGLTJk6_8epien-2Ftmdiuf-X7gtI8dxpnqIAQozz67lHU02SMfl1Jn0sdTxoBWsyYZI6lel6hJffGXX3AwVfSz6vkgiyfD8ZjxShq7GpwaDgjqfo0FDNYDMdTjkLZxjx5P7sS?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/nYLDGQoiioCXs15RX0ReydB9cCLeib8GDpmXc3ioB7_9uZZMSUYFGRgRr0dnTap3iOWTWPNrjuev7I0cQb-AYSjh8mNzDO-oSarFslJyq21zaMDo-BRSyNFOvLkND13msigHZot91KrMF0aQNH-7q2wrhOpcdRLcofwUhl3mF5GU0SDzhGqzLs69GLHvs3QL?purpose=fullsize)

**Scattering** occurs when a radio wave encounters **small objects or rough surfaces** whose dimensions are comparable to or smaller than the wavelength.

Instead of bouncing in one well-defined direction, the signal energy is redirected in **many different directions**.

**Examples:**

* Trees and foliage
* Street signs
* Lamp posts
* Rough terrain
* Wire fences
* Small objects

**Effect:** Scattering creates many weak signal components arriving at the receiver from different directions. This can cause signal fluctuations and fading.

---

## Simple Diagram

```text
                         Reflection
                    ↗  ↗  ↗
                   / Building
                  /  ███████
                 /   ███████
                /    ███████
               /
      Tx  ●────────────────────────● Rx
             Direct Path
                  \
                   \       Diffraction
                    \     ↘ around edge
                     \   █████
                      \  █
                       \ █

             ~ ~ ~ ~ ~ ~ ~ ~
               Scattering
             ↗  ↑  ↖  →  ↘
            small objects
```

### Comparison

| Feature            | Reflection                      | Diffraction                      | Scattering                    |
| ------------------ | ------------------------------- | -------------------------------- | ----------------------------- |
| **Main action**    | Bounces the wave                | Bends/spreads the wave           | Diffuses wave energy          |
| **Occurs around**  | Large, smooth surfaces          | Edges and obstacles              | Small objects/rough surfaces  |
| **Signal paths**   | Creates reflected paths         | Allows paths around obstacles    | Creates many weak paths       |
| **Predictability** | Relatively predictable          | Can be mathematically modeled    | More random/statistical       |
| **Example**        | Signal bouncing from a building | Signal bending around a building | Signal interacting with trees |
| **Major effect**   | Multipath                       | NLOS propagation                 | Multipath and fading          |

### Easy Way to Remember

**Reflection → Bounce**
**Diffraction → Bend around an edge**
**Scattering → Spread in many directions**

Together, these mechanisms cause **multipath propagation**, where multiple copies of the transmitted signal reach the receiver through different paths. These copies can reinforce or cancel one another, producing **multipath fading and signal distortion**.


# 2. Compare Reflection, Diffraction and Scattering. Give suitable examples for each.

## Comparison of Reflection, Diffraction and Scattering

In wireless communication, **reflection, diffraction, and scattering** are the three important propagation mechanisms that determine how electromagnetic waves travel through real-world environments. The main difference between them depends on the **size, shape, and surface characteristics of the object** encountered by the radio wave.

### Comparison Table

| Feature            | Reflection                                     | Diffraction                                                                                            | Scattering                                               |
| ------------------ | ---------------------------------------------- | ------------------------------------------------------------------------------------------------------ | -------------------------------------------------------- |
| **Object Size**    | Much larger than the wavelength                | Obstruction/edge affects the wave path; edge dimensions are typically large relative to the wavelength | Objects are smaller than or comparable to the wavelength |
| **Primary Effect** | Bounces the wave from a surface                | Bends/spreads the wave around edges                                                                    | Spreads energy in many directions                        |
| **Surface Nature** | Smooth or large flat surfaces                  | Sharp edges or obstacles                                                                               | Rough surfaces or small objects                          |
| **Predictability** | Highly predictable; follows laws of reflection | Can be modeled using wave/diffraction theory                                                           | More random; usually analyzed statistically              |
| **Main Result**    | Creates reflected signal paths                 | Enables signal propagation into shadow regions                                                         | Creates many weak signal components                      |
| **Example**        | Signal reflecting from a building              | Signal bending around a building or hill                                                               | Signal scattering from trees and foliage                 |

---

## 1. Reflection

![Image](https://images.openai.com/static-rsc-4/ZYqPq9FMI7Kz_Zpv6VsFHRYYTj7u3Mt-fLr50q8QV9z5ba2D7cmklq12YGxya_HDlFupe-tyVIaGQBBmibnkXvW7dk4--zqE6FXgBeSZ1HTSvILAp-GOcKoscrFxDeL486MNmoCRYIyLuOLWtyKFphsLsgh4m8YS8mMCMCsl7rubji_KTVObYOWwlSQNmxZl?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/rtsuEVzkZAk8210jKT_jYosFkSZlCP_3_oo9ynn1Q4r9vy_ol5NN8g4EaJycCt1UXh_qX6Db1DiLEkqZ4h0aXg1TuTe1N5IsSmiN9DwzckXs2LusQRRzM1J10zJ9WNBiESotTrQnD9sit6kCcwSFCUQh0DQIwLi6r7bDJvNflpDnQOXwmJ1Q9WMAHgDYu13S?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/TDNJ1leNPscEoMaUgYIfDe_mfJxCYnRj8INu41mrO77tGCsVzUDS4kpzEoiHNPvE0mWfdOTvj5TLpOaRhFN9AiNKO7Gfo1t16ggb-sj8lhNwZTggkOHkIqS549zF24pAgo2zL2S1RWz8BXi7Ao0zTZwx0WoIhh1HzMorh4gMEBlKC_MXwjhXwduCYQNyXGi7?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/Kh5iKaCXF3fwEHwZjxhK_xYnrruWSQMrozfdFKKz8rWLWDtrRKybwLMeAVbwDotSDm3mLsVvdZlt5P4Y56SYfAJgwi0NE4xjxeyJbu9oWtC2kOUsZXIQ8MG2UOc7HW7ovmfEVRiVZPkN07zjlJ0FCMM0UyAKCkGw-FjdrQ8mm4J19cqxTTZTl0o4ET40HnMi?purpose=fullsize)

**Reflection** occurs when a radio wave encounters a **large, smooth surface**.

The wave is redirected from the surface according to the law:

$$
\boxed{\theta_i=\theta_r}
$$

where:

* \(\theta_i\) = angle of incidence
* \(\theta_r\) = angle of reflection

### Examples

**Outdoor:**

* Large buildings
* Roads
* Water surfaces
* Earth's surface

**Indoor:**

* Walls
* Doors
* Glass
* Metal cabinets

### Effect

Reflection creates an additional path between the transmitter and receiver. The reflected signal may combine with the direct signal and cause **constructive or destructive interference**, resulting in multipath fading.

---

## 2. Diffraction

![Image](https://images.openai.com/static-rsc-4/8No8nhGpgCbhu-bhBISboAIMBwR04iltn-xzHE0hbD0H3sHaukPta7x12DE3IKXjHNzFAAhXUMPNLaU2kuzB5roguT1BfCxdAXpmMsIgBOmHRI2nDoZPZFV-rnlTM_mCh8M5i5cuECXoElb5pUbPbQrF79E1Q6S2zBYLJWrGpda02CGuCVQ06cgCvVg_2WH1?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/xcTZ6Rz_Eht9OgC_4iSU_taivqkbSG9eQrDT93Sc_ZsB__J5i2-p_iV-XHDDO1WSRp85TZFx1_cTeW3TA8FAceNHNl0ntJFrO_ALx659iZPhVAkWnYo3GEg4D3ellO7l3T8ZYKMZ_396VXNJPiikCGkyv_JzyVtBGFLp62pFDFkF5nusEGUNLnnlXK5TomU1?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/cxoGFEGMVUSfDxAsTQ09vIzLyNjgQA1FuOYuX7DV96JkTUjwAduGxA1XfaavCgkcI9gQhS8ozDsC9c3B77Y8CkKhif3k4vbxepzkvzBJdQ3OxoLkPceT4kSvAMl90ZBM-QXpTvJznIwDiDA-PKaLAUVwxOtlX9nVRMCrLUMwmH0wTD9YTgDJV188tiEZlUq5?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/0iXwudqDxKWx2qYMfUmoHcwngoC9ZAzxnAsRDB685cARGQZDXr1lqb8cQjpusXwM1nNV5LEbkMcO-0M0csoVsc4g2DyNy2v0K3bVFQj7z6O0t5spN1vbzuRGJv_McPV3rLX9UqSEgvW-_1QispmZj4I07VD8PX1JDfhbPPzfikIvvAI-0tDOhxPo5xB37jhY?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/jb4az3Nm1lAJAhOgWC4CmXljOX49SJ2YMnPhizS71yxZVBSPbj7nc9E1ziC4RRTgeTniO6C-5HNSdnoaxVdhkYr3-tLBRcTACwYr9A031AY9wAPE_NMfLR8lowuvgf7LHrV8DbW2vCch9RmcgGGLq5c_fRl4v6_5X4sJB6uT7dGmCl0UjahKdmlDeekhmS4G?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/KCQMOW6mB4cFdsCKyvSfObuYhRtVqNNruRbEUYWw5K82GB8X-ALUdC5KwqFV0Uz7wwng_PqYQVAutXgK0PTTROBPdtHGbdyRzV_zveVjaQSCgaN3NHaAalOuMUEsTvxpYk3v0qZh2KPvgUCqNLWb0Ls0-m-85EEFoC_OC-R3gHGzeIgPIwEepANw5xBXscA6?purpose=fullsize)

**Diffraction** occurs when a radio wave encounters an **obstruction or sharp edge**. The wave bends and spreads into the region behind the obstacle.

It is particularly important for **Non-Line-of-Sight (NLOS)** communication.

### Examples

* Radio signal bending around a building
* Signal reaching a receiver behind a hill
* Waves bending around mountains or large obstacles

### Effect

Diffraction allows a receiver to receive a signal even when the **direct path is blocked**.

However, the diffracted signal is generally weaker than the direct signal.

**Easy analogy:** You can sometimes hear sound around a corner even though you cannot directly see the source.

---

## 3. Scattering

![Image](https://images.openai.com/static-rsc-4/jjwx66lxfslgFktM1h17iW4pCaPOQYhfRug1F7BGO87TqsR4zQ3NCXzjRgvY6vGf5LZuQhL9OhWjylkOtjMVFHS7BVXwsAiwhi8jQIgF5rovKoaqAsb4bkyrcxng-lzCex8glYdz9qqYC-0AC00bUV7E3bAKxlTOcAL5THLjb4RCzw13ekIT_4juMmZ-kD_F?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/e71wFT-KZsLHQ4SLFv5jJowX-ci6PFRmQndInS2Wh53PrDB7Biux9tZJTE8pHGmoP78KQgvs81_M4i1DgPRu9inJGiMoHvcSNeDZhZ8z48wLG2tgQvKnIhV7RsOsztHrGHESlO2VihXWQkeu1F3ffVKTOFyvsfSCr6lZqUhxkr97e7GWM0IwPjOLx_3e_4uZ?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/Kh5iKaCXF3fwEHwZjxhK_xYnrruWSQMrozfdFKKz8rWLWDtrRKybwLMeAVbwDotSDm3mLsVvdZlt5P4Y56SYfAJgwi0NE4xjxeyJbu9oWtC2kOUsZXIQ8MG2UOc7HW7ovmfEVRiVZPkN07zjlJ0FCMM0UyAKCkGw-FjdrQ8mm4J19cqxTTZTl0o4ET40HnMi?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/xyQJQYn884OlWBxjRebMhboDDUdla5hvusTKqmcXled1j1gbc2gQAUuD5yTB272HgDaiRlUV1Aen_KZgjBE_OQ09egUcUMnxvu1R-X28LSnIJt6YTdgxnw-L9psO899t39TF_ASK5DlhF3-fd0aTrU5vTYhvYmSGkv7E8NN_MxkuS1ftqD4tUtOSeJKqOyAq?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/qytxtRLt52vAK-w5QJTW5wtss8WZ3iOyTtTpVNKlqJXoO8RkHT5HfXR-z8CGLTJk6_8epien-2Ftmdiuf-X7gtI8dxpnqIAQozz67lHU02SMfl1Jn0sdTxoBWsyYZI6lel6hJffGXX3AwVfSz6vkgiyfD8ZjxShq7GpwaDgjqfo0FDNYDMdTjkLZxjx5P7sS?purpose=fullsize)

**Scattering** occurs when a radio wave encounters **small objects or rough surfaces** whose dimensions are comparable to or smaller than the wavelength.

Instead of being redirected in one particular direction, the electromagnetic energy is distributed in **many directions**.

### Examples

* Tree leaves and branches
* Street signs
* Lamp posts
* Rocky surfaces
* Wire meshes
* Rough terrain

### Effect

Scattering produces many weaker signal components arriving at the receiver from different directions. This contributes to **multipath propagation and fading**.

---

## Simple Diagram

```text
                         REFLECTION
                            ↗
                           /
                          /  Large building
                         /   █████████
                        /    █████████
                       /     █████████
                      /
             Tx ●────────────────────────● Rx
                   Direct path

                         DIFFRACTION
                              ↘
                               ↘ around edge
                                █████
                                █
                                █

             SCATTERING
                  ↗   ↑   ↖
                   \  |  /
                    \ | /
                  small objects
```

### Easy Way to Remember

> **Reflection → Bounce**
> **Diffraction → Bend around an obstacle**
> **Scattering → Spread in many directions**

### Conclusion

The three mechanisms work together in a real wireless environment. **Reflection** creates additional paths by bouncing signals from large surfaces, **diffraction** allows signals to reach shadowed regions around obstacles, and **scattering** distributes signal energy in many directions due to small objects or rough surfaces.

Together, they produce **multipath propagation**, which is a major cause of **small-scale fading, delay spread, interference, and signal distortion** in wireless communication.


# 3. Explain Multipath Propagation. What are the effects of multipath propagation on wireless communication?

# Multipath Propagation in Wireless Communication

**Multipath propagation** occurs when a transmitted radio signal reaches the receiver through **multiple different paths** due to reflection, diffraction, and scattering from objects in the environment.

![Image](https://images.openai.com/static-rsc-4/Iw7Z31xarWXkIDmNGlCDpUCJb_3zdmPLz-r-lO_d1ySI6MTTiQOx8HAiLdDzqF27aRTo8HetLQKwIOtzejwcgQ928K7Vfaq1elP8qoNEAU2XmVyZrcJDGsrNZwvYGPvfP9vG0CzpM2DnDcYTx1JKwdEjDY369OLCqlqkYDeD8N4YXJEIM-_DN4FnyfP-q6FN?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/Kh5iKaCXF3fwEHwZjxhK_xYnrruWSQMrozfdFKKz8rWLWDtrRKybwLMeAVbwDotSDm3mLsVvdZlt5P4Y56SYfAJgwi0NE4xjxeyJbu9oWtC2kOUsZXIQ8MG2UOc7HW7ovmfEVRiVZPkN07zjlJ0FCMM0UyAKCkGw-FjdrQ8mm4J19cqxTTZTl0o4ET40HnMi?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/hVksXgAQyrXD9OJlL52LkhnhUv3eWZZaDl0ng7mu_dNA8ok6W5chCzWjVWGPMFnoGxIUx6dtwei7jR1hrgAL_YSSMJTg9pfSN-tE5zSwBq-ZSf920iF6s_qmOscIwddb8-vx6hOtloglxBTWS-t6aECXPQln_8CmQzKawTANhkhZeaO_Ff6TpDt7rUQotIOa?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/Ur8cAWQNAUoRnToZgExE7QDEEuF2yvoA9qnTCkVECccvW_m_HshgIiJFLYI1GrlHSTd68Lfk-aHBm9vHjPSUz3Wh8lIfCp5nNvGix7-shrILDU0nWH_WREIyqBZgDVsOwTJSAkFYnYC7cGVocldzcrQ8EE14yOrFMHovAY97GN0tBeBjSouOjtlqsb-QW5vi?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/L8cWn_FbB_0okDCNxBdLoClGGxOCSxsOVu36miqVcuRni7m_UzxEu5Nc_XXjYnW_FvXNkl4942vcodTmDKWODsW3MP86Y18PYyHIR2i6kCGms7A0a9wbQRbGTAnJQcK3JzXwLqpx7q_OEf8BTZwG7WTe2S-xtoDYUp_4Y6CCiD2Z88AH8GsafdV9eGw4UOTo?purpose=fullsize)

For example, in an urban area, a signal can reach the receiver through:

* **Direct path** from transmitter to receiver
* **Reflected path** from buildings
* **Diffracted path** around obstacles
* **Scattered paths** from trees, vehicles, and other objects

Since these paths have different lengths, the signal components arrive at the receiver at **different times, amplitudes, and phases**.

---

## Effects of Multipath Propagation

### 1. Small-Scale Fading

When multiple copies of a signal arrive at the receiver, they combine with one another.

* If they arrive **in phase**, they reinforce each other.
* If they arrive **out of phase**, they partially or completely cancel each other.

This causes rapid changes in received signal strength over small distances or short periods of time.

This phenomenon is called **small-scale fading**.

A severe cancellation can produce a **deep fade**, where the received signal becomes extremely weak.

---

### 2. Multipath Delay Spread

Different paths have different lengths, so the signal components arrive at different times.

```text
Signal
  |
  |       Direct path
  |       ↓
  |       █
  |       █       Reflected path
  |       █       ↓
  |       █   █
  |       █   █       Scattered path
  |       █   █   █
  +--------------------------> Time
          t₁  t₂  t₃
```

The difference between the arrival times of different multipath components is called **delay spread**.

A common statistical measure is the **RMS (Root Mean Square) delay spread**.

---

### 3. Inter-Symbol Interference (ISI)

In digital communication, information is transmitted using consecutive **symbols**.

When a previous symbol arrives late because of multipath propagation, it can overlap with the next symbol.

```text
Without ISI:

Symbol 1     Symbol 2     Symbol 3
██████       ██████       ██████


With ISI:

Symbol 1        Symbol 2
████████████████████
       ↑
   Overlap
```

This overlap is called **Inter-Symbol Interference (ISI)**.

ISI can cause:

* Incorrect symbol detection
* Increased bit errors
* Data corruption
* Reduced communication reliability

---

### 4. Frequency-Selective Fading

Multipath propagation can affect different frequency components of a signal differently.

When the **delay spread is large**, different frequencies may experience different amounts of attenuation.

This produces **frequency-selective fading**.

In contrast, when the delay spread is small compared with the symbol duration, the channel can behave approximately as a **flat-fading channel**, where the signal's frequency components are affected more uniformly.

---

## Relationship Between Delay Spread and Fading

| Condition                | Channel Behavior                      |
| ------------------------ | ------------------------------------- |
| Small delay spread       | Approximately flat fading             |
| Large delay spread       | Frequency-selective fading            |
| Different path lengths   | Different arrival times               |
| Different arrival phases | Constructive/destructive interference |
| Large delay spread       | Greater possibility of ISI            |

A useful concept is **coherence bandwidth**: a channel with a small delay spread generally has a larger coherence bandwidth, while a channel with a large delay spread generally has a smaller coherence bandwidth.

---

# Techniques to Reduce Multipath Effects

### 1. Equalization

An **equalizer** at the receiver compensates for the distortion caused by multipath propagation and helps reduce **ISI**.

It attempts to reconstruct the original transmitted signal from the distorted received signal.

---

### 2. Diversity

**Diversity** uses multiple independently fading versions of the signal.

Examples include:

* **Spatial diversity** — multiple antennas
* **Frequency diversity** — different frequency channels
* **Time diversity** — transmission at different times

The basic idea is:

> If one signal path experiences a deep fade, another independent path may still have a strong signal.

Combining these signals improves communication reliability.

---

### 3. Adaptive Modulation

The transmitter/receiver can change the modulation scheme according to current channel conditions.

For example:

* **Good channel:** higher-order modulation such as 16-QAM or 64-QAM → higher data rate
* **Poor channel:** more robust modulation such as QPSK → better reliability

Thus, adaptive modulation provides a balance between **data rate and reliability**.

---

## Overall Concept

```text
                         Building
                      ↗────────────↘
                     /              \
                    /   Reflection   \
                   /                  \
              ┌─────────┐
              │         │
        Tx ●──┤ Wireless├────────────────● Rx
              │ Channel │
              └─────────┘
                 ↘     ↗
                  ↘   ↗
                Scattering

                   ↓
            Multiple Paths
                   ↓
       Different delays & phases
                   ↓
          ┌─────────────────┐
          │ Multipath       │
          │ Propagation     │
          └─────────────────┘
                   ↓
       ┌───────────┼───────────┐
       ↓           ↓           ↓
    Fading     Delay Spread    ISI
       ↓           ↓           ↓
   Signal       Time         Data
 fluctuation   dispersion    errors
```

### Exam Definition

> **Multipath propagation is the phenomenon in which a transmitted radio signal reaches the receiver through multiple paths due to reflection, diffraction, and scattering. Since the different paths have different lengths, the signal components arrive at different times, amplitudes, and phases, resulting in fading, delay spread, ISI, and frequency-selective fading.**

**In short:**
**Reflection + Diffraction + Scattering → Multiple paths → Different delays/phases → Multipath fading + Delay spread → ISI and signal degradation.**


# 4. Explain Large-Scale Fading and Small-Scale Fading. Compare the two types of fading.

# Fading in Wireless Communication

**Fading** refers to the variation or fluctuation in the **strength, amplitude, and quality of a radio signal** as it travels from the transmitter to the receiver. It occurs because of factors such as **distance, obstacles, multipath propagation, and movement** between the transmitter and receiver.

Fading is broadly classified into:

1. **Large-Scale Fading**
2. **Small-Scale Fading**

---

## 1. Large-Scale Fading

![Image](https://images.openai.com/static-rsc-4/Lpt3shvb-fC5Ife5iEovCbF8gJPaNqsmZKw4-J4GtJwpq1d3WJCAuPFv7Ok70Vnq0FgTnVhOnT5SyFMFEPdKymlRTMEiT3dhfqPGWgRKqzImSXSUGuXETGMuGdvuD2n0VssF9Waffm4zwxXEapL8Ad6ynBGE0coVtThqXufVlZeMHgZGJ9pv9iUCQXy98246?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/X3UgZ9EQXiY_to2admJTVF3uEQwJcHyxtec4KJqk0oN_NEhbNHDJe5eN7iUx6zAcr4Jera5OOa7Cral1jym-3qdFKtMMOB2P7wWyOK-dSGjKTq-wqJ44siCw7KiZXUqK-Y2nA50YXuOEerC1eXATjFrMDSJblP6ng2RPaw1PKUNGSvsTwr6BY0PqJS920YWO?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/4X-edN_u94ODxQVPc49DimMJRi2aGAiKHmelMwH9tkQ3Vz_OQ0gcZCpHxqlSZ8iFse7tx6h6bDUNnFDbqr4BFqqdsOMV_lS-7U2wWWb_bHlo4cx5KiI2jH0KDCuQKONwAir1jTX6067XdWIZsh6SpXnUvZuEtd_bT1XOiNH89oY927R1p7-haDTNEM0J1vFF?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/x30aykeImfEb55vR2Tt9PIvQSZr4zH7EeUyaWOs2uNkcwg278Cj8T_ChBq-rqbjSJGV2aQ_L64R23AQmiQ_kS3MTYa1yOw6MnT02VIIJI8udHaRKb8ytCUhXJf3PB_cm8jz2jjdoD-8100G92yfaLUOO470OMxsxhIq_ZvtaunY1Ss2C-n7IUuMbcRYCUeDT?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/cRJWiSVAtUbJ4S_vGSrxPVHGo1uu9vu4LUOgs7j4BMZrJs2nqiP85dH34boqw8xZraNitM0KPU6CUuQd3P7pP-4IHbNQLg6CIpgG0sij7RAgFbHpdv0wELAvBzMzZri8TFlBWWJmAro5dL7k3MSA9hP3fVne2G55X2yKGSPqqByy65ixOfHWV6YMEux36RHE?purpose=fullsize)

**Large-scale fading** represents the gradual variation in the **average received signal power** over relatively large distances.

It is mainly associated with **path loss and shadowing**.

### Main Causes

* Increasing distance between transmitter and receiver
* Large buildings
* Hills and mountains
* Other large physical obstructions
* General characteristics of the propagation environment

### Components

#### A. Path Loss

**Path loss** is the reduction in average signal power as the distance between the transmitter and receiver increases.

It depends on factors such as:

* Distance
* Frequency
* Antenna characteristics
* Propagation environment

#### B. Shadowing

**Shadowing** occurs when large obstacles block or partially obstruct the signal path.

For example:

```text
       Building
       ███████
       ███████
       ███████
          ↓
Tx ● ─────█──────────── ● Rx
          ↓
      Shadowed region
```

Shadowing causes the received power to vary around its average value and is generally modeled statistically using a **log-normal distribution**.

### Characteristics

* Slow variation
* Occurs over relatively large distances
* Mainly affects **average received power**
* Caused primarily by path loss and large-scale obstructions

### Mitigation

Large-scale fading can be reduced using:

* Power control
* Proper antenna placement
* Repeaters
* Site/cell diversity

---

# 2. Small-Scale Fading

![Image](https://images.openai.com/static-rsc-4/ZYqPq9FMI7Kz_Zpv6VsFHRYYTj7u3Mt-fLr50q8QV9z5ba2D7cmklq12YGxya_HDlFupe-tyVIaGQBBmibnkXvW7dk4--zqE6FXgBeSZ1HTSvILAp-GOcKoscrFxDeL486MNmoCRYIyLuOLWtyKFphsLsgh4m8YS8mMCMCsl7rubji_KTVObYOWwlSQNmxZl?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/UV1Luo2hjwEl5DgGpZOe87xTnztmFmsbTJ0iHP3Y4qwKQ8dqJGbHGAm4VZw4tc98eJJxFPjMQxOupVRTqToQ3EQ1iRqm_FVO_du6GsiLwspkk06E51JQ1H4bma6xtLJFbFoqvLPiUhlGyMUdMwAVXtJ-zF_IgO9voPzlKwQC1kopRnR_VDYB_mWxEGFi00eP?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/stb04NFs8P3MkUtQIPCR66aiMayHcZD3j4G-j3MCQx4mjP0YlQ4JnokxUO8R-2BzHD_8HSWj1ZpFopmaB85Njo3DSrtksbzKuPfFUEgiBx40kjc3gqc3atf01sXNuZvXw_OabcIDTslQn3YXhcEXjViuWzT4AhdzHUTSuWfW1xN7aB3SkmDwrZxzRpJcrVYv?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/sqiy886Kv_8-fgfQRcpJnCp2V4ChhpEYW8pPMpgvBs8zYcg3t6-UqmwrGBpIC46P4bJwF9lXuo1LaQ_WZTCAM8OwLD4L3SkDwJwCzBvjfDmAH6UcksiSH3ZyjtftyPQ8DJuzMuIwG9JianOC1W8xpjnDdt5vIDmjTexhlGADvtFQKnVOJimWVoN9usOSTdme?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/K0eXkboyYpsZ4RyifwUQN7Yt_cQbyjMcnNPcsMc1nqmvFVViIRPE5WiRVJ3dpSY0Zn1AjcZF8jzD6P34ZMTUST4eYdns46p2ETZdpcbdczpMBqHYl3dYctTha6_UwGfK5UjohxRaKCMyibXZCs0LVfWYLgIGx_KJzaUK6M5tPt55oPkbp-pzn_FdElLSklva?purpose=fullsize)

**Small-scale fading** refers to rapid variations in the **received signal amplitude and phase** over short distances or short periods of time.

Its primary cause is **multipath propagation**.

Radio waves can reach the receiver through several paths because of:

* Reflection
* Diffraction
* Scattering

The different signal components arrive with different **amplitudes, phases, and delays**.

```text
                     Reflection
                    ↗──────────↘
                   /            \
                  /              \
             Tx ●────────────────● Rx
                  \              /
                   ↘            ↗
                    Scattering

              Multiple signal paths
                        ↓
              Different delays/phases
                        ↓
              Constructive / destructive
                    interference
                        ↓
                 Small-scale fading
```

### Constructive and Destructive Interference

When multipath components arrive **in phase**, they reinforce one another:

$$
\text{Constructive interference} \rightarrow \text{strong signal}
$$

When they arrive **out of phase**, they cancel one another:

$$
\text{Destructive interference} \rightarrow \text{weak signal/deep fade}
$$

Therefore, the received signal can change significantly even when the receiver moves only a small distance.

---

## Important Components of Small-Scale Fading

### A. Multipath Delay Spread

Different paths have different lengths, so the copies of the signal arrive at different times.

This creates **delay spread**.

If the delay spread is large enough, consecutive symbols can overlap, producing:

$$
\boxed{\text{Inter-Symbol Interference (ISI)}}
$$

The **RMS delay spread** is commonly used to statistically characterize this time dispersion.

A large delay spread can result in a **frequency-selective channel**, while a sufficiently small delay spread corresponds approximately to **flat fading**.

---

### B. Doppler Spread

When either the transmitter or receiver is moving, the received signal experiences a **Doppler shift**.

For a simple direct-path case:

$$
f_D=\frac{v}{\lambda}\cos\theta
$$

where:

* \(f_D\) = Doppler shift
* \(v\) = relative velocity
* \(\lambda\) = wavelength
* \(\theta\) = angle between the direction of motion and wave arrival

Doppler effects cause the wireless channel to vary with time and can therefore produce rapid changes in the received signal.

---

# Small-Scale vs Large-Scale Fading

| Parameter                | Small-Scale Fading                           | Large-Scale Fading                                          |
| ------------------------ | -------------------------------------------- | ----------------------------------------------------------- |
| **Variation**            | Rapid                                        | Slow                                                        |
| **Main cause**           | Multipath propagation                        | Path loss and shadowing                                     |
| **Distance scale**       | Short distances, often a few wavelengths     | Much larger distances                                       |
| **Time variation**       | Fast                                         | Slow                                                        |
| **Main effect**          | Rapid amplitude/phase fluctuations           | Gradual change in average received power                    |
| **Signal paths**         | Multiple paths are important                 | Average propagation path is important                       |
| **Major problems**       | Deep fades, delay spread, ISI                | Reduced signal strength, coverage holes                     |
| **Important parameters** | RMS delay spread, Doppler spread             | Path-loss exponent, shadowing variation                     |
| **Mitigation**           | Equalization, diversity, adaptive modulation | Power control, antenna placement, repeaters, site diversity |

---

## Easy Way to Remember

### Large-Scale Fading

**Large obstacles + long distance → slow change in average signal power**

It mainly consists of:

$$
\boxed{\text{Path Loss + Shadowing}}
$$

### Small-Scale Fading

**Multiple paths + movement → rapid signal fluctuations**

It is associated with:

$$
\boxed{\text{Multipath Delay Spread + Doppler Spread}}
$$

---

## Exam Definition

> **Fading is the variation in the received signal strength, amplitude, or phase caused by changes in the propagation environment, distance, multipath propagation, and relative movement between the transmitter and receiver. It is broadly classified into large-scale fading, which describes slow variations in average received power due to path loss and shadowing, and small-scale fading, which describes rapid variations caused mainly by multipath propagation and Doppler effects.**

### One-Line Summary

$$
\boxed{\text{Large-Scale Fading → Path Loss + Shadowing}}
$$

$$
\boxed{\text{Small-Scale Fading → Multipath + Doppler Effects}}
$$


# 5. Explain Doppler Effect and Coherence Time in wireless communication.

# Doppler Effect and Coherence Time

The **Doppler Effect** and **Coherence Time** describe how a wireless channel changes with **time**, especially when the transmitter, receiver, or surrounding objects are moving.

The basic relationship is:

$$
\boxed{\text{Higher Doppler Spread} \Rightarrow \text{Faster Channel Variation} \Rightarrow \text{Smaller Coherence Time}}
$$

---

## 1. Doppler Effect

![Image](https://images.openai.com/static-rsc-4/Gdfzf2kow2V6G_Wbvpdg1ue-WONRkYWhcZO_7sdw5GAyn772fT8Z9C_x9A9MEYbaC-Z8dvUVDziuRxJwJEKcpWpg2HBxaEPBxFsZnj4uDSj8q_Kwj-xYKBKu0f9ZqM-7Mg4PXYvxJ7g5mN73IGxqOSXjvz3kaWFNoMzNbJmRdwptZk2PXoCYJUTVe3fhzR3_?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/S8bg9wcZf0sQ5FUZm_H9gjvwe2F27gkqPR09TH8mUspN0jlFp8ulc6i6OviPXuT1Om2a9mwx111cMzRzfdxgqV0ZL-OHxb83ffgVwzHZNpkZSR205QpzUGMwPqc-8npHJjecjgF95b6IQJ7PLnt5MQhz_AvVNvKXkeQXsUGBSSV3wMKqxwT9stHDJlhbIi-1?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/HhzuL1JSg7ucOYtvy-qNfcTDXncvXz_UGdowkqxw5lKVRw2vrBv8EM7TGoCgOL8p9TdZGjUAfcAIrqJZFiiRhyJh4Sz7kIyWNEVxEqoFptriKY0LeCE7kIWoh8XXBmi81eQINWQLYhJKqdi6_-H0WNYuL26aIN0j80GvuihHHcr555LQZ5cV8KpGbnveJj4Y?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/Vh54kEeVfiy0LQ2gG2FVUL006p-kzZOVhufPtBr-ZUf3wgAqJ2OLm6Kg8tIdUFrLYA6yNskoFgHcHUpAi-5zz2l9HjWI1W3XRIRYKQzlhFc6INhl-LrN-B9SY7QJA_ygI2WpFu96QDmHtTySPbWDY8KfuI5UGcmyMOoTm8tv-h_bjnJCMhS-UzVgCcfKn44y?purpose=fullsize)

The **Doppler Effect** is the change in the observed frequency of a radio signal caused by **relative motion between the transmitter and receiver**.

For a moving receiver, the Doppler shift can be expressed as:

$$
\boxed{f_D=\frac{v}{\lambda}\cos\theta}
$$

where:

* \(f_D\) = Doppler shift
* \(v\) = relative velocity
* \(\lambda\) = wavelength
* \(\theta\) = angle between the direction of motion and the arriving wave

The maximum Doppler shift occurs when the receiver moves directly toward or away from the transmitter:

$$
\boxed{f_m=\frac{v}{\lambda}}
$$

Since:

$$
\lambda=\frac{c}{f_c}
$$

we can also write:

$$
\boxed{f_m=\frac{vf_c}{c}}
$$

where \(f_c\) is the carrier frequency and \(c\) is the speed of light.

### Example

If a mobile user moves quickly, the received signal frequency changes more rapidly. Therefore, the wireless channel becomes **more time-varying**.

---

# 2. Doppler Spread

In a multipath environment, signals arrive at the receiver from **different directions**. Each path can experience a different Doppler shift.

Therefore, instead of receiving one shifted frequency, the received signal can occupy a range of frequencies.

This range is called the **Doppler spread**, denoted by \(B_D\).

A simplified representation is:

```text
                    Doppler Spectrum

                         Power
                           ↑
                           │
                           │       ███
                           │     ███████
                           │   ███████████
                           │____███████████____
                           └────────────────────→ Frequency
                             fc-fm    fc    fc+fm
```

Approximately:

$$
\boxed{B_D \approx 2f_m}
$$

Thus:

* **High Doppler spread** → rapid channel variation
* **Low Doppler spread** → slow channel variation

---

# 3. Coherence Time

![Image](https://images.openai.com/static-rsc-4/2kG2uw-yZfr-bmjzYGJ1ZyCqxigqR7Eqvshjm0Ae31aO2tWubIgjGpu4X8_Ic5VmI3TeEEIafhXORywQ4NLlEdoM3PeGQytclWaczyBrwXvULHqEBBCSQKgAA_2mQfRz_3lWHmwYK5j30kABgM00vrRqq-QilPCMISgA1QOcSLn-3Bs8jGPQBtIajxF_gxxI?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/Bw2txKS9Zz7sCrBpGD2yrZwtaeF15p7fL-h5A5dKPtI3zE5COGIE_Z9DfraYHqUGBV1KpxH3OC5wsqSMn3td0AaouPpR2FIMUH6TA8xkBhIpBws-eMiwr-CIM2en1ySSKFlFs_4aG6mQJZlKIxcRFn3U9Y6LmSXd-aPoztXASG8mKq73YMueByjkDnLs7PRF?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/AuVcphDoT3PGO0Lp5Qxuvo8xnZNYpfBCqoxVBwIqwBW4al64r-JUTqxQfqwMg8YqeAkeulIt9Q3QioJ00X6n68xke1TIjSX7VWMma0VAvvBgItzg89Qc0YfmMCisBG9_qxr8RZ0OvYUGlP_0CVerlDG76nlzr4Cjkn-ibS6A5RKVrKtGVfHk4FReypZCNvoU?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/YecbN8SXa1H5ZZp2Rqj5to0IjIDb1VJKCcimC5qvmhFRx_YmO1eeMt5O7G6bFT0pqRypnSaL3rJqvjPsFeJbjQ2gkh9sgUfZDgrCI_VJSEIB_R1saCmLQ-1ZXws6mWMXGQPoPeSbaw3Ghr2lKuVXKCgrNpDYjWqGdheVRYDaWM0Rjx4YYbizPFVB9_ix0hr4?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/u6rtKgJgxF68EeX-eqd_yl61KhEKS1fApFA7kc_ldtfthlxV__XXL-kPLijOyqVjp6Dn-0QnaDGoCHN5b_GKZKHjY7z4npwJwuh9Ee4MmOed9GftSrZ47QV7nsgh_SF0wXBJMUfIg3aegoorvdU5h3LlQjhLHGJhI_BcCgmKHkQ0ScJmCEqqIXekMENgrsd5?purpose=fullsize)

**Coherence time \(T_C\)** is the approximate time duration over which the wireless channel remains **strongly correlated or approximately unchanged**.

In simple terms:

> **Coherence time tells us how long the wireless channel can be considered stable.**

If two signals are transmitted within a period shorter than the coherence time, they are likely to experience **similar channel conditions**.

If they are separated by a time much greater than the coherence time, they may experience significantly different channel conditions.

---

## 4. Relationship Between Doppler Spread and Coherence Time

Doppler spread and coherence time are approximately **inversely related**.

### Basic approximation

$$
\boxed{T_C\approx\frac{1}{f_m}}
$$

Therefore:

$$
f_m\uparrow \quad\Rightarrow\quad T_C\downarrow
$$

and

$$
f_m\downarrow \quad\Rightarrow\quad T_C\uparrow
$$

### Practical approximation

A commonly used approximation is:

$$
\boxed{T_C\approx\frac{0.423}{f_m}}
$$

This is often useful in wireless-system calculations.

---

## 5. Example

Suppose the maximum Doppler shift is:

$$
f_m=100\text{ Hz}
$$

Using the practical approximation:

$$
T_C=\frac{0.423}{100}
$$

$$
\boxed{T_C=0.00423\text{ s}=4.23\text{ ms}}
$$

This means the channel can be considered approximately stable over a time scale of a few milliseconds.

---

# 6. Doppler Effect vs Coherence Time

| Parameter            | Doppler Spread                          | Coherence Time                                |
| -------------------- | --------------------------------------- | --------------------------------------------- |
| **Meaning**          | Range of Doppler frequency shifts       | Duration for which channel remains correlated |
| **Symbol**           | \(B_D\) or \(f_m\)                      | \(T_C\)                                       |
| **Unit**             | Hz                                      | Seconds                                       |
| **Depends on**       | Relative velocity and carrier frequency | Doppler characteristics                       |
| **High value means** | Faster channel variation                | Shorter channel stability                     |
| **Low value means**  | Slower channel variation                | Longer channel stability                      |
| **Relationship**     | Increases with mobility                 | Decreases with mobility                       |

---

## Easy Way to Remember

Think of a **person walking vs a person sitting** while using a mobile phone:

```text
Low mobility
     ↓
Low Doppler spread
     ↓
Slow channel variation
     ↓
Large coherence time


High mobility
     ↓
High Doppler spread
     ↓
Fast channel variation
     ↓
Small coherence time
```

### Important Connection with Small-Scale Fading

Doppler spread and coherence time are important characteristics of **small-scale fading**:

$$
\boxed{\text{Motion} \rightarrow \text{Doppler Shift} \rightarrow
\text{Doppler Spread} \rightarrow \text{Time-Varying Channel}}
$$

and

$$
\boxed{\text{Higher Doppler Spread} \leftrightarrow
\text{Shorter Coherence Time}}
$$

### Exam Definition

> **Doppler spread is the range of frequencies produced by Doppler shifts in a time-varying wireless channel due to relative motion. Coherence time is the time duration over which the channel remains approximately unchanged or highly correlated. Doppler spread and coherence time are inversely related: higher mobility produces greater Doppler spread and a shorter coherence time.**

# 6. Explain FDMA, TDMA and CDMA. Compare these multiple access techniques.

# Multiple Access Techniques in Wireless Communication

**Multiple Access Techniques** are methods that allow multiple users to share the same communication medium or radio spectrum while minimizing interference between them.

The three important techniques are:

1. **FDMA – Frequency Division Multiple Access**
2. **TDMA – Time Division Multiple Access**
3. **CDMA – Code Division Multiple Access**

---

## 1. FDMA — Frequency Division Multiple Access

![Image](https://images.openai.com/static-rsc-4/SJOR360lBecLTuK8D1sZfPKtqEIDLmFhIiXiS8gVsyJ503Vc-B6BUy9JRvAwsWajGLHfeLCo2jfvwcHxBKQbo0cbPs2WMWFOMvegu5Db9AP1X2ERD_V2TcIbvnBRKD91mioVW1bH_LgmBBqFpXdWq93mvXs3xQzoiDL5_0Ze0VGu_QruI9HmBq0Is9l7DYgk?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/xqCm8JqLWooP_G0dqh19z2KqnASrNdN9cGK-K-DEta5BI11J4Jl5lgMaIiaiRIEk8a12QldYlzvyCzFPoP7aQLctKayAs5L-tzXdhajmV4cD8TYPRtT6usvwa_QKEa3ofQ878460kKxZWpwVfus508mzdo6FFma9DIFjioxu_2BAKdawoij86OH-7_S_8b8C?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/iNJb911WwqsF5E5Ugh1NRLXCAD9LwU60SxNPe8Ph9G3KVOskOrboxujv0aW1RUDvSKIKKoJFV9J5g3kG6AHcr9PqT18H25xvYyhzebv5dj60BHIeNNa2TAEpfKqb2H8Z7s0f7-GgCnmtpKKUMUOFaoP77zeX87qBskf-PYxjaPze3TlUPP8cPu0v6ypWi-VY?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/SMa70wE9gIBELnZhtvFriuCv-SK5Xpz2ljTR4UP7IzXUXEIBWPuV6ZTdAlmCBhVy-ORt3C9TjJy0Cgdxm7dYKW-PqyazuBqlBBkZvweKo_GGatgOqF3Jzpk0atA88HzSYDax52STx_T-5bcIQuo4vv4aZdqXju5UbLjPVkdd8LcW-iscPoQ_8ZD3i-pMzynu?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/iRztAk9Ufw-I4GGAHd8m3Dp20rXcm897QKDxyB1PxQRvCz0a3_WC2Ezw-rfszcimsprxyFX810Shd28I5VjfVQNZyPKhtSdPoUgm16pE7TPEgO5hqLQAFLT1sYGd1foKrNfMA3r0RrtWz7oSi9FGcEikTRQ1YmFO6U8CCvkg4YiVTzdno7-JOyuS1XYkUsYU?purpose=fullsize)

In **FDMA**, the available frequency spectrum is divided into separate **frequency bands**, and each user is assigned a different frequency band.

```text id="f8t3v5"
Frequency
   ↑
   │  User 3 ─────────────
   │          Guard Band
   │  User 2 ─────────────
   │          Guard Band
   │  User 1 ─────────────
   └────────────────────────→ Time
```

Each user can transmit **continuously** on their assigned frequency.

### Characteristics

* Spectrum is divided into frequency bands.
* Each user gets a dedicated frequency.
* **Guard bands** separate adjacent channels.
* Users transmit continuously.
* Time synchronization between users is not required.
* Relatively simple technique.
* Traditionally associated with analog cellular systems.

### Example

If the available spectrum is divided into three bands:

$$
f_1 \rightarrow \text{User 1}
$$

$$
f_2 \rightarrow \text{User 2}
$$

$$
f_3 \rightarrow \text{User 3}
$$

All three users can communicate **at the same time**, but on different frequencies.

---

# 2. TDMA — Time Division Multiple Access

![Image](https://images.openai.com/static-rsc-4/k2WvauZo3OQwMmPi9lymoxNPCWH1umJ2i4NNUOhTuCWCOsu-WzTNHAkYlvCS-b1iU1Rnsg3adI6mZ1mzNbedo1pu_xqyDbl8jkQs6_oZmpHisgr-1_yq7NMa6sPZ1Tg4JJEN5ONcO9m3StZPLgkiPlUCOdKU6DlHeCG7aH7hRhqN90ENIgDR0o5yInBuMxUj?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/p7QcPlAnhbCWJCtZEOLwRHlcIPalqcX6b5D8EOB-hs6h41-g26KIpe0EKD681VPya9-V13dIdfBh1KBGZ5on9U7viLfVIjFCcMNtz5Yz52Y6l_Yda4E60sAlD7Sv28WlRIsaKG6uhiRx2cIGbk7bi4lhhPbI2RUwsr0ZlXSkwLLOOqccUpZV85E1iBHbuqRu?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/hIZjY_SPs5kaVCIlLG2JoGlR1a8gmrGztyl3qK-hcmE2WOOLppwIJfS-_iQ0hjLaAxWg3_TzwGkvqTKU84k8VxqGv7Ef43hHKFzTTfuxt9k5k9S2_sdO83G2oGnEaWUBuFaluzA6HqNNJu40_EXHRcfSYZRgFHwqZvnP0KyQzJsHDLxiF-VdUEuSNPO2qiwQ?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/JWp2Mya1Vvd4rQz_pIDcyAW4OPZqDIXbEd6u77L-vF-wB65ZmBMVQn6PSyPvhdnpDEqLBJC0JhhEJbakjPXbyK5Dmm17gejUq_XWLvOEyMahWPkRYaTMiQqSju_hA_pJqSP0LDrYvADRMLmSP-FNLnNoCerSu2Ma6UNbLnbT-PvTzrohIxfX6LpqHPs2pSls?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/Xg1aB8zgQfXASUjxlmZtLzgwQVZpMvuYp3QGfiHbWM6T6snu0EPF2IZtB-ES3uwNulqYVqxOiKZtIUr2JI6dyrA7e5NMlcXKGbcCmaOVNSotTZpPGJ-tZUsNU4nxHrsIxFdsg_SmL_fn9cW8nPR4ySYUNGMTK8WG2_-2U514vigtiizoXtT2OGOSADyBfZpt?purpose=fullsize)

In **TDMA**, multiple users share the **same frequency**, but each user is assigned a different **time slot**.

```text id="4c1mve"
Time →
┌────────┬────────┬────────┬────────┬────────┬────────┐
│ User 1 │ User 2 │ User 3 │ User 1 │ User 2 │ User 3 │
└────────┴────────┴────────┴────────┴────────┴────────┘
            ↑
        Time slots
```

Each user transmits only during their assigned slot.

### Guard Time

A small interval called **guard time** may be inserted between slots to prevent overlap caused by propagation delays and timing uncertainties.

```text
User 1 | GT | User 2 | GT | User 3 | GT |
```

### Characteristics

* Users share the same frequency.
* Each user receives a specific time slot.
* Requires **time synchronization**.
* Transmission occurs in **bursts**.
* Guard time helps prevent slot overlap.
* The transmitter can remain inactive outside its assigned slot, which can help conserve battery power.
* Primarily used with digital communication systems.

---

# 3. CDMA — Code Division Multiple Access

![Image](https://images.openai.com/static-rsc-4/m5qg2qWqYK8JnOoh0BVnFeS63F9B6Bfi16HQe2EzTjay1bGU47g9XkNeda6_XqJAhwtaHER5vq0IpsxCFGDcYNaN26KI-8XjKXASkmMkI2GRkqi7HxmrkM13iyEtIhiWqGNeD9dJFqL1vgLHgCozgXKRm84vLs6kRJSLl6-qZnv8bwUJJN1_gulBjtJ_nJL3?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/VMPWOnLFYf1RwbT_y9itY9G9sFcv_b2pOxSbmhGW_9Jl1IcTKnVb2eyeVVa0F-go8iNM5nL8l6_--GJ2MMhOrjxxlwCNHsgPIeCHoGGBRGJMvniRuYvEdaM0vkVhVxC7zjx2Lp3FkotKb2SO08vVVga6od4tIKEWUzp_3Cj_kdNeTmEfh-01MrhJKhptRL_5?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/rF5bkoRYN4uHofW5wu-Cxjl9YR_Hap3QVKbQbEWgw8t273RUvu_OLajA2JryKJC7s1yxuP0aG6JiwNh-lEGAaDHhfrxGO7Er8lR53luAXnIv6Y9Q6NwCgrddfp7Cv1Tqv8w-EOQABxPuhxQ4xjhR4SMBRAN04mA1JAD5bLdaf1suidCEHQLRLQoFxVWMH7jZ?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/BAozkvUHqvqcXSInkTfY4Kb-UsT09Tk6hhw9SDkL0DKVmJCs4QpoeVTemysII11MODQaygjsMRJ1vlR8MFNUo6PUy5dTRymjMwaouggzT4ECEki48R_N59b3ID5vtxAmBTSUjPC1-nrUIWuPFTl3c1bUnIDLUbLU8-tDqrRRZCFFRpe7lhm9SI-CvPz-dl9L?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/i7OaSZFNT6YOV_MniH1OW-oQTX1PKl9kmiw-BgfSDLRrILlj_QZPW6SNF6BHcDCnuqKG06q8G9dSWilFVq5oGWk0neocofzrwO6svYLnNafjJn_WAZjtLKLqfJOSomJilzf346FojyVYrFekGjUXFcHR9Gsr1xsIjZ-gzqVaNme65Sam8mTsYSGmxkfLvc12?purpose=fullsize)

In **CDMA**, multiple users can transmit **at the same time and over the same frequency band**.

Users are separated using different **code sequences**.

```text
             Same Frequency Band
                    ↓
     ┌─────────────────────────────┐
     │ User 1 → Code 1             │
     │ User 2 → Code 2             │
     │ User 3 → Code 3             │
     │ User 4 → Code 4             │
     └─────────────────────────────┘
                    ↓
              Shared Channel
                    ↓
        Receiver uses desired code
                    ↓
             User's data
```

The user's data is multiplied/spread using a high-rate code before transmission.

At the receiver, the corresponding code is used to **despread and recover the desired user's signal**.

### Characteristics

* Users share the same frequency band.
* Users can transmit simultaneously.
* Users are distinguished using codes.
* Requires sophisticated signal processing.
* Provides good resistance to interference and multipath when properly designed.
* Commonly associated with spread-spectrum digital systems.

> **Important correction:** Unlike FDMA and TDMA, CDMA does **not inherently require both guard bands and guard times** to separate users. User separation primarily comes from the codes and the receiver's correlation/despreading process. System-specific timing or frequency guard intervals can exist for other engineering reasons.

---

# FDMA vs TDMA vs CDMA

| Feature                 | **FDMA**                                | **TDMA**                      | **CDMA**                                                         |
| ----------------------- | --------------------------------------- | ----------------------------- | ---------------------------------------------------------------- |
| **Full Form**           | Frequency Division Multiple Access      | Time Division Multiple Access | Code Division Multiple Access                                    |
| **Users separated by**  | Frequency                               | Time                          | Code                                                             |
| **Frequency usage**     | Different frequency bands               | Same frequency                | Same frequency                                                   |
| **Time usage**          | Continuous                              | Different time slots          | Simultaneous                                                     |
| **Code required?**      | No                                      | No                            | Yes                                                              |
| **Guard requirement**   | Guard bands                             | Guard times                   | No inherent guard band/time for user separation                  |
| **Synchronization**     | Relatively simple                       | Time synchronization required | Code/timing synchronization and system coordination are required |
| **Transmission**        | Continuous                              | Bursts                        | Simultaneous spread-spectrum transmission                        |
| **Hardware complexity** | Lower                                   | Moderate                      | Higher                                                           |
| **Main advantage**      | Simple frequency separation             | Efficient time sharing        | Many users can share the same spectrum simultaneously            |
| **Main limitation**     | Wastes spectrum when a user is inactive | Requires accurate timing      | More complex interference and power management                   |

---

## Easy Way to Remember

The easiest way to distinguish the three is:

$$
\boxed{\text{FDMA → Different Frequencies}}
$$

$$
\boxed{\text{TDMA → Different Times}}
$$

$$
\boxed{\text{CDMA → Different Codes}}
$$

### Visual Summary

```text
FDMA
Frequency ↑
          │ User 3 ─────────
          │ User 2 ─────────
          │ User 1 ─────────
          └────────────────→ Time


TDMA
Frequency ↑
          │ ┌────┬────┬────┐
          │ │ U1 │ U2 │ U3 │
          │ └────┴────┴────┘
          └────────────────→ Time


CDMA
Frequency ↑
          │ U1 ─────────────
          │ U2 ─────────────    Same frequency
          │ U3 ─────────────    + same time
          └────────────────→ Time
               Different codes
```

## Exam Answer

> **Multiple Access Techniques are methods used to allow multiple users to share a common communication medium efficiently. FDMA separates users by assigning different frequency bands, TDMA separates users by assigning different time slots, and CDMA allows users to share the same frequency and time but distinguishes them using unique spreading codes.**

### One-Line Trick

**FDMA = Frequency** → **TDMA = Time** → **CDMA = Code**.

