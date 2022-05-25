# NCC-Product-Card

Este es un paquete de pruebas de despliegue en NPM

### Nicolás Cousillas

```
import {ProductCard, ProductImage, ProductTitle, ProductButtons} from 'ncc-product-card';
```

```
<ProductCard
    key={ product.id }
    product={ product }
    initialValues={{
        count: 4,
        maxCount: 10
    }}
>
    {
        ({ reset, increaseBy, isMaxCountReached, count, maxCount }) => (
            <>
                <ProductImage />
                <ProductTitle />
                <ProductButtons />
            </>
        )
    }
</ProductCard> 
```