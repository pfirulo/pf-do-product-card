Este es un paquete de pruebas de despliegue NPM
### Pablo Firulo

## Ejemplo
```
 import {ProductCard,ProductImage, ProductTitle, ProductButtons} from pf-do-product-card
```
 ```
    <>
      <ProductCard
        product={product}
        initialValues={{
          count: 4,
          maxCount: 10
        }}>
        {({ reset, count, increaseBy, isMaxCountRached, maxCount }) => (
          <>
            <ProductImage />
            <ProductTitle />
            <ProductButtons />
          </>
        )}
      </ProductCard>
    </>
```
          