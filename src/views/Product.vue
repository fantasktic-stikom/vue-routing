<template>
    <div>
        <h1>This is a product page</h1>
        <div class="container">
            <ul>
                <li><router-link to='/product/1'>Product 1</router-link></li>
                <li><router-link :to="{name: 'detailProduct', params: {productId: 2}}">Product 2</router-link></li>
            </ul>
        </div>
    </div>
</template>