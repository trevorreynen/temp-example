<template>
    <div class="homepage-content">
        <div class="card-grid">

            <div class="card">
                <div class="card-inner"
                     :class="{ flip: cardOneFaceUp }"
                     @click="cardOneFaceUp = !cardOneFaceUp">

                    <div class="card-back">
                        <img :src="image[0]" />
                    </div>

                    <div class="card-front">
                        <header class="card-header">
                            <h1>Card One</h1>
                        </header>
                        <div class="card-body">
                            <p>Card One content</p>
                        </div>
                        <footer class="card-footer">
                            <p>Card One footer</p>
                        </footer>
                    </div>

                </div>
            </div>

            <div class="card">
                <div class="card-inner"
                     :class="{ flip: cardTwoFaceUp }"
                     @click="cardTwoFaceUp = !cardTwoFaceUp">

                    <div class="card-back">
                        <img :src="image[1]" />
                    </div>

                    <div class="card-front">
                        <header class="card-header">
                            <h1>Card Two</h1>
                        </header>
                        <div class="card-body">
                            <p>Card Two content</p>
                        </div>
                        <footer class="card-footer">
                            <p>Card Two footer</p>
                        </footer>
                    </div>

                </div>
            </div>

            <div class="card">
                <div class="card-inner"
                     :class="{ flip: cardThreeFaceUp }"
                     @click="cardThreeFaceUp = !cardThreeFaceUp">

                    <div class="card-back">
                        <img :src="image[2]" />
                    </div>

                    <div class="card-front">
                        <header class="card-header">
                            <h1>Card Three</h1>
                        </header>
                        <div class="card-body">
                            <p>Card Three content</p>
                        </div>
                        <footer class="card-footer">
                            <p>Card Three footer</p>
                        </footer>
                    </div>

                </div>
            </div>

            <div class="card">
                <div class="card-inner"
                     :class="{ flip: cardFourFaceUp }"
                     @click="cardFourFaceUp = !cardFourFaceUp">

                    <div class="card-back">
                        <img :src="image[3]" />
                    </div>

                    <div class="card-front">
                        <header class="card-header">
                            <h1>Card Four</h1>
                        </header>
                        <div class="card-body">
                            <p>Card Four content</p>
                        </div>
                        <footer class="card-footer">
                            <p>Card Four footer</p>
                        </footer>
                    </div>

                </div>
            </div>

            <div class="card">
                <div class="card-inner"
                     :class="{ flip: cardFiveFaceUp }"
                     @click="cardFiveFaceUp = !cardFiveFaceUp">

                    <div class="card-back">
                        <img :src="image[4]" />
                    </div>

                    <div class="card-front">
                        <header class="card-header">
                            <h1>Card Five</h1>
                        </header>
                        <div class="card-body">
                            <p>Card Five content</p>
                        </div>
                        <footer class="card-footer">
                            <p>Card Five footer</p>
                        </footer>
                    </div>

                </div>
            </div>

            <div class="card">
                <div class="card-inner"
                     :class="{ flip: cardSixFaceUp }"
                     @click="cardSixFaceUp = !cardSixFaceUp">

                    <div class="card-back">
                        <img :src="image[5]" />
                    </div>

                    <div class="card-front">
                        <header class="card-header">
                            <h1>Card Six</h1>
                        </header>
                        <div class="card-body">
                            <p>Card Six content</p>
                        </div>
                        <footer class="card-footer">
                            <p>Card Six footer</p>
                        </footer>
                    </div>

                </div>
            </div>

            <div class="card">
                <div class="card-inner"
                     :class="{ flip: cardSevenFaceUp }"
                     @click="cardSevenFaceUp = !cardSevenFaceUp">

                    <div class="card-back">
                        <img :src="image[6]" />
                    </div>

                    <div class="card-front">
                        <header class="card-header">
                            <h1>Card Seven</h1>
                        </header>
                        <div class="card-body">
                            <p>Card Seven content</p>
                        </div>
                        <footer class="card-footer">
                            <p>Card Seven footer</p>
                        </footer>
                    </div>

                </div>
            </div>

            <div class="card">
                <div class="card-inner"
                     :class="{ flip: cardEightFaceUp }"
                     @click="cardEightFaceUp = !cardEightFaceUp">

                    <div class="card-back">
                        <img :src="image[7]" />
                    </div>

                    <div class="card-front">
                        <header class="card-header">
                            <h1>Card Eight</h1>
                        </header>
                        <div class="card-body">
                            <p>Card Eight content</p>
                        </div>
                        <footer class="card-footer">
                            <p>Card Eight footer</p>
                        </footer>
                    </div>

                </div>
            </div>

            <div class="card">
                <div class="card-inner"
                     :class="{ flip: cardNineFaceUp }"
                     @click="cardNineFaceUp = !cardNineFaceUp">

                    <div class="card-back">
                        <img :src="image[8]" />
                    </div>

                    <div class="card-front">
                        <header class="card-header">
                            <h1>Card Nine</h1>
                        </header>
                        <div class="card-body">
                            <p>Card Nine content</p>
                        </div>
                        <footer class="card-footer">
                            <p>Card Nine footer</p>
                        </footer>
                    </div>

                </div>
            </div>

            <div class="card">
                <div class="card-inner"
                     :class="{ flip: cardTenFaceUp }"
                     @click="cardTenFaceUp = !cardTenFaceUp">

                    <div class="card-back">
                        <img :src="image[9]" />
                    </div>

                    <div class="card-front">
                        <header class="card-header">
                            <h1>Card Ten</h1>
                        </header>
                        <div class="card-body">
                            <p>Card Ten content</p>
                        </div>
                        <footer class="card-footer">
                            <p>Card Ten footer</p>
                        </footer>
                    </div>

                </div>
            </div>

        </div>
    </div>
</template>

<script>
    import axios from 'axios'

    export default {
        name: 'Homepage',
        data() {
            return {
                cardOneFaceUp: false,
                cardTwoFaceUp: false,
                cardThreeFaceUp: false,
                cardFourFaceUp: false,
                cardFiveFaceUp: false,
                cardSixFaceUp: false,
                cardSevenFaceUp: false,
                cardEightFaceUp: false,
                cardNineFaceUp: false,
                cardTenFaceUp: false,
                image: []
            }
        },
        mounted() {
            this.getImage()
        },
        methods: {
            async getImage() {
                axios
                    .get('https://dog.ceo/api/breeds/image/random/10')
                    .then((response) => {
                        console.log(response.data)
                        this.image = response.data.message
                    })
                    .catch((error) => {
                        console.log(error)
                    })

            }
        }
    }
</script>

<style scoped>
    @import url('https://fonts.googleapis.com/css2?family=Open+Sans&display=swap');

    .homepage-content {
        width: 95%;
        margin: 20px auto;
        padding: 10px;
        text-align: center;
        font-family: 'Open Sans', sans-serif;
        background: #eee;
        border-radius: 5px;
        box-shadow: 5px 5px 5px #ccc;
    }

    .card-grid {
        display: grid;
        grid-template-columns: repeat(5, auto);
        grid-gap: 10px;
    }

    .card {
        max-width: 300px;
        height: 350px;
        border-radius: 15px;
        background-color: transparent;
        perspective: 1000px;
    }

    .card-inner {
        position: relative;
        width: 100%;
        height: 100%;
        transition: transform 0.8s;
        transform-style: preserve-3d;
    }

    .card .card-back, .card .card-front {
        position: absolute;
        width: 100%;
        height: 100%;
        backface-visibility: hidden;
    }

    .card .card-back {
        background-color: #bbb;
    }

    .card .card-front {
        transform: rotateY(180deg);
        background: #bbb;
    }

    .card .card-inner.flip {
        transform: rotateY(180deg);
    }

    .card-back img {
        width: 100%;
        height: 100%;
    }
</style>

