# ELBP-Product-Card

Este es un paquete de pruebas de despliege en NPM


### Enrique Luis

## Ejemplo

```
import {ProductCard,ProductImage,ProductTitle, ProductButtons } from 'elbp-product-card';
```
```
 <ProductCard
        product={product}
        initialValues={{
          count: 4,
          maxCount: 7
        }}
      >
        {
          ({ reset, isMaxCountReached, count, increaseBy }) => (
            <>
              <ProductImage/>
              <ProductTitle />
              <ProductButtons />
            </>
          )
        }

      </ProductCard>
```