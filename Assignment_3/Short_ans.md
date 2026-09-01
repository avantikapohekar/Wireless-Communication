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

# 3. Explain Multipath Propagation. What are the effects of multipath propagation on wireless communication?

# 4. Explain Large-Scale Fading and Small-Scale Fading. Compare the two types of fading.

# 5. Explain Doppler Effect and Coherence Time in wireless communication.

# 6. Explain FDMA, TDMA and CDMA. Compare these multiple access techniques.
