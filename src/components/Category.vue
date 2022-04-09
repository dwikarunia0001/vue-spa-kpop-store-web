// eslint-disable-next-line vue/multi-word-component-names
<template>
    <div class="container">
        <div class="row mt-5">
            <h3>Trending</h3>
            <div class="col">
                <div class="list-group">
                    <a href="#" class="list-group-item list-group-item-action d-flex gap-3 py-3" aria-current="true">
                        <img src="https://upload.wikimedia.org/wikipedia/en/thumb/5/54/Red_Velvet_-_The_ReVe_Festival_2022_-_Feel_My_Rhythm.png/220px-Red_Velvet_-_The_ReVe_Festival_2022_-_Feel_My_Rhythm.png" alt="twbs" width="32" height="32" class="rounded-circle flex-shrink-0">
                        <div class="d-flex gap-2 w-100 justify-content-between">
                        <div>
                            <h6 class="mb-0">The ReVe Festival 2022 - Red Velvet</h6>
                        </div>
                        <small class="opacity-50 text-nowrap">now</small>
                        </div>
                    </a>
                    <a href="#" class="list-group-item list-group-item-action d-flex gap-3 py-3" aria-current="true">
                        <img src="https://upload.wikimedia.org/wikipedia/en/c/c3/Shinee_-_Don%27t_Call_Me.png" alt="twbs" width="32" height="32" class="rounded-circle flex-shrink-0">
                        <div class="d-flex gap-2 w-100 justify-content-between">
                        <div>
                            <h6 class="mb-0">Atlantis - Shinee</h6>
                        </div>
                        <small class="opacity-50 text-nowrap">3d</small>
                        </div>
                    </a>
                    <a href="#" class="list-group-item list-group-item-action d-flex gap-3 py-3" aria-current="true">
                        <img src="https://upload.wikimedia.org/wikipedia/id/4/41/IU_-_Lilac.png" alt="twbs" width="32" height="32" class="rounded-circle flex-shrink-0">
                        <div class="d-flex gap-2 w-100 justify-content-between">
                        <div>
                            <h6 class="mb-0">Lilac - IU</h6>
                        </div>
                        <small class="opacity-50 text-nowrap">1w</small>
                        </div>
                    </a>
                </div>
            </div>
        </div>
    </div>

    <div class="album py-5 bg-light">
        <div class="container">
            <h2 class="pb-2 border-bottom">Best Seller</h2>
        <div class="row row-cols-1 row-cols-sm-2 row-cols-md-3 g-3">
            <div class="col">
            <div class="card shadow-sm">
                <img src="https://upload.wikimedia.org/wikipedia/en/0/0d/Red_Velvet_-_The_ReVe_Festival_Finale.png" alt="reve1">

                <div class="card-body">
                <div class="text-card">
                    <h4>Red Velvet The ReVe Festival: Finale</h4>
                    <p>Red Velvet</p>
                </div>
                </div>
            </div>
            </div>
            <div class="col">
            <div class="card shadow-sm">
                <img src="https://upload.wikimedia.org/wikipedia/zh/c/cf/NCT_2020_RESONANCE_Pt._1.jpg" alt="nct1">

                <div class="card-body">
                <div class="text-card">
                    <h4>NCT RESONANCE Pt. 1</h4>
                    <p>NCT 2020</p>
                </div>
                </div>
            </div>
            </div>
            <div class="col">
            <div class="card shadow-sm">
                <img src="https://upload.wikimedia.org/wikipedia/en/b/b5/Snsdigotaboyalbum.jpg" alt="snsd1">

                <div class="card-body">
                <div class="text-card">
                    <h4>I Got a Boy</h4>
                    <p>Girls Generation</p>
                </div>
                </div>
            </div>
            </div>
        </div>

        </div>
    </div>

    <div class="container px-4 py-5" id="custom-cards">
        <h2 class="pb-2 border-bottom">Terbaru</h2>

        <div class="row row-cols-1 row-cols-lg-3 align-items-stretch g-4 py-5">
        <div class="col">
            <div class="card card-cover h-100 overflow-hidden text-white bg-dark rounded-5 shadow-lg" style="background-image: url('https://upload.wikimedia.org/wikipedia/en/thumb/7/79/Ive_%E2%80%93_Love_Dive.jpg/220px-Ive_%E2%80%93_Love_Dive.jpg');">
            <div class="d-flex flex-column h-100 p-5 pb-3 text-white text-shadow-1">
                <h2 class="pt-5 mt-5 mb-4 display-6 lh-1 fw-bold">Short title, long jacket</h2>
                <ul class="d-flex list-unstyled mt-auto">
                <li class="me-auto">
                    <img src="https://github.com/twbs.png" alt="Bootstrap" width="32" height="32" class="rounded-circle border border-white">
                </li>
                <li class="d-flex align-items-center me-3">
                    <svg class="bi me-2" width="1em" height="1em"><use xlink:href="#geo-fill"/></svg>
                    <small>Earth</small>
                </li>
                <li class="d-flex align-items-center">
                    <svg class="bi me-2" width="1em" height="1em"><use xlink:href="#calendar3"/></svg>
                    <small>3d</small>
                </li>
                </ul>
            </div>
            </div>
        </div>

        <div class="col">
            <div class="card card-cover h-100 overflow-hidden text-white bg-dark rounded-5 shadow-lg" style="background-image: url('https://upload.wikimedia.org/wikipedia/id/5/54/Red_Velvet_-_The_ReVe_Festival_2022_-_Feel_My_Rhythm.png');">
            <div class="d-flex flex-column h-100 p-5 pb-3 text-white text-shadow-1">
                <h2 class="pt-5 mt-5 mb-4 display-6 lh-1 fw-bold">Much longer title that wraps to multiple lines</h2>
                <ul class="d-flex list-unstyled mt-auto">
                <li class="me-auto">
                    <img src="https://github.com/twbs.png" alt="Bootstrap" width="32" height="32" class="rounded-circle border border-white">
                </li>
                <li class="d-flex align-items-center me-3">
                    <svg class="bi me-2" width="1em" height="1em"><use xlink:href="#geo-fill"/></svg>
                    <small>Pakistan</small>
                </li>
                <li class="d-flex align-items-center">
                    <svg class="bi me-2" width="1em" height="1em"><use xlink:href="#calendar3"/></svg>
                    <small>4d</small>
                </li>
                </ul>
            </div>
            </div>
        </div>

        <div class="col">
            <div class="card card-cover h-100 overflow-hidden text-white bg-dark rounded-5 shadow-lg" style="background-image: url('https://upload.wikimedia.org/wikipedia/en/thumb/1/12/NCT_Dream_-_Glitch_Mode.jpg/220px-NCT_Dream_-_Glitch_Mode.jpg');">
            <div class="d-flex flex-column h-100 p-5 pb-3 text-shadow-1">
                <h2 class="pt-5 mt-5 mb-4 display-6 lh-1 fw-bold">Another longer title belongs here</h2>
                <ul class="d-flex list-unstyled mt-auto">
                <li class="me-auto">
                    <img src="https://github.com/twbs.png" alt="Bootstrap" width="32" height="32" class="rounded-circle border border-white">
                </li>
                <li class="d-flex align-items-center me-3">
                    <svg class="bi me-2" width="1em" height="1em"><use xlink:href="#geo-fill"/></svg>
                    <small>California</small>
                </li>
                <li class="d-flex align-items-center">
                    <svg class="bi me-2" width="1em" height="1em"><use xlink:href="#calendar3"/></svg>
                    <small>5d</small>
                </li>
                </ul>
            </div>
            </div>
        </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<style scoped>

</style>