<template>
    <!-- Carousel Start -->
    <div class="container-fluid p-0 mb-5 pb-5">
        <div id="header-carousel" class="carousel slide carousel-fade" data-bs-touch="false" data-bs-interval="false">
            <div class="carousel-inner">
                <div class="carousel-item active" data-bs-interval="5000">
                    <img class="w-100" src="/src/assets/img/background1.jpg" alt="Image">
                    <div class="carousel-caption d-flex flex-column align-items-center justify-content-center">
                        <div class="p-3" style="max-width: 900px;">
                            <h4 class="text-white text-uppercase mb-md-3">Space & Traditional</h4>
                            <h1 class="display-3 text-white mb-md-4">Quiet And Trendy Space</h1>
                            <a href="" class="btn btn-secondary py-md-3 px-md-5 mt-2">Learn More</a>
                        </div>
                    </div>
                </div>
                <div class="carousel-item" data-bs-interval="5000">
                    <img class="w-100" src="/src/assets/img/background2.jpg" alt="Image">
                    <div class="carousel-caption d-flex flex-column align-items-center justify-content-center">
                        <div class="p-3" style="max-width: 900px;">
                            <h4 class="text-white text-uppercase mb-md-3">Space & Traditional</h4>
                            <h1 class="display-3 text-white mb-md-4">Traditional Pho Xuyen Cafe</h1>
                            <a href="" class="btn btn-secondary py-md-3 px-md-5 mt-2">Learn More</a>
                        </div>
                    </div>
                </div>
            </div>
            <a class="carousel-control-prev" href="#header-carousel" data-slide="prev">
                <div class="btn btn-secondary px-0" style="width: 45px; height: 45px;">
                    <span class="carousel-control-prev-icon mb-n1"></span>
                </div>
            </a>
            <a class="carousel-control-next" href="#header-carousel" data-slide="next">
                <div class="btn btn-secondary px-0" style="width: 45px; height: 45px;">
                    <span class="carousel-control-next-icon mb-n1"></span>
                </div>
            </a>
        </div>
    </div>
    <!-- Carousel End -->

    <!-- About Start -->
    <div class="container-fluid py-2">
        <div class="container py-2">
            <div class="row justify-content-center">
                <div class="col-lg-7">
                    <h1 class="section-title position-relative text-center mb-5">Space & Traditional
                        Pho Xuyen Cafe</h1>
                </div>
            </div>
            <div class="row">
                <div class="col-lg-4 py-5">
                    <h3 class="font-weight-bold mb-3">About Us</h3>
                    <h5 class="text-muted mb-3">Nếu bạn đang tìm kiếm một quán cà phê với không gian thoải mái và thân thiện, 
                        hãy ghé thăm Phố Xuyên Cafe </h5>
                    <p>Quán cà phê Phố Xuyên tại Thành phố Long Xuyên là một nơi thân thiện,
                         nơi chúng tôi muốn tạo ra không gian yên tĩnh và mát mẻ. 
                         Quán phục vụ nhiều loại đồ uống và món ăn ngon ngay tại trung tâm thành phố</p>
                    <a href="" class="btn btn-secondary mt-2">Learn More</a>
                </div>
                <div class="col-lg-4" style="min-height: 400px;">
                    <div class="position-relative h-100 rounded overflow-hidden">
                        <img class="position-absolute w-100 h-100" src="/src/assets/img/about.jpg"
                            style="object-fit: cover;">
                    </div>
                </div>
                <div class="col-lg-4 py-5">
                    <h3 class="font-weight-bold mb-3">Our Features</h3>
                    <p>Phố Xuyên Cafe là tổ hợp nghệ thuật, kết hợp giữa mô hình cafe, triển lãm và workshop. Tại Phố Xuyên Cafe, bạn có thể:</p>
                    <h5 class="text-muted mb-3"><i class="fa fa-check text-secondary me-3"></i>Nhâm nhi ly cafe buổi sáng: Thả mình vào không gian yên tĩnh, thưởng thức hương vị đậm đà của cà phê.</h5>
                    <h5 class="text-muted mb-3"><i class="fa fa-check text-secondary me-3"></i>Hẹn hò trà chiều cùng bạn bè: Tận hưởng không gian thoải mái, trò chuyện và thư giãn.</h5>
                    <h5 class="text-muted mb-3"><i class="fa fa-check text-secondary me-3"></i>Tham gia các workshop thú vị: Học hỏi, sáng tạo và kết nối với cộng đồng nghệ sĩ và đam mê nghệ thuật.</h5>
                    <h5 class="text-muted mb-3"><i class="fa fa-check text-secondary me-3"></i>Cho thuê và tổ chức sự kiện: Tạo ra những khoảnh khắc đáng nhớ cho bạn và người thân</h5>
                    <a href="" class="btn btn-secondary mt-2">Learn More</a>
                </div>
            </div>
        </div>
    </div>
    <!-- About End -->

    <!-- Services Start -->
    <div class="container-fluid py-5">
        <div class="container py-5">
            <div class="row">
                <div class="col-lg-6">
                    <h2 class="section-title position-relative mb-5">Những nước uống yêu thích</h2>
                </div>
                <div class="col-lg-6 mb-5 mb-lg-0 pb-5 pb-lg-0"></div>
            </div>
            <div class="row">
                <div class="col-12">
                    <div class="owl-carousel row">
                        <div class="service-item col-3">
                            <div class="service-img mx-auto">
                                <img class="rounded-circle w-100 h-100 bg-success p-3" src="src/assets/img/service-1.jpg"
                                    style="object-fit: cover;">
                            </div>
                            <div class="position-relative text-center bg-success rounded p-4 pb-5" style="margin-top: -75px;">
                                <h5 class="font-weight-semi-bold mt-5 mb-3 pt-5 text-white">Milk Coffee</h5>
                                <p class="text-white">OUR. - Where Art and Coffee Blend.</p>
                                <a href="" class="border-bottom border-secondary text-decoration-none text-secondary">Learn
                                    More</a>
                            </div>
                        </div>
                        <div class="service-item col-3">
                            <div class="service-img mx-auto">
                                <img class="rounded-circle w-100 h-100 bg-success p-3" src="src/assets/img/service-2.jpg"
                                    style="object-fit: cover;">
                            </div>
                            <div class="position-relative text-center bg-success rounded p-4 pb-5" style="margin-top: -75px;">
                                <h5 class="font-weight-semi-bold mt-5 mb-3 pt-5 text-white">Milk Tea</h5>
                                <p class="text-white">OUR. - Where Art and Coffee Blend.</p>
                                <a href="" class="border-bottom border-secondary text-decoration-none text-secondary">Learn
                                    More</a>
                            </div>
                        </div>
                        <div class="service-item col-3">
                            <div class="service-img mx-auto">
                                <img class="rounded-circle w-100 h-100 bg-success p-3" src="src/assets/img/service-3.jpg"
                                    style="object-fit: cover;">
                            </div>
                            <div class="position-relative text-center bg-success rounded p-4 pb-5" style="margin-top: -75px;">
                                <h5 class="font-weight-semi-bold mt-5 mb-3 pt-5 text-white">Strawberry Yogurt</h5>
                                <p class="text-white">OUR. - Where Art and Coffee Blend.</p>
                                <a href="" class="border-bottom border-secondary text-decoration-none text-secondary">Learn
                                    More</a>
                            </div>
                        </div>
                        <div class="service-item col-3">
                            <div class="service-img mx-auto">
                                <img class="rounded-circle w-100 h-100 bg-success p-3" src="src/assets/img/service-4.jpg"
                                    style="object-fit: cover;">
                            </div>
                            <div class="position-relative text-center bg-success rounded p-4 pb-5" style="margin-top: -75px;">
                                <h5 class="font-weight-semi-bold mt-5 mb-3 pt-5 text-white">Syrup Mix</h5>
                                <p class="text-white">OUR. - Where Art and Coffee Blend.</p>
                                <a href="" class="border-bottom border-secondary text-decoration-none text-secondary">Learn
                                    More</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- Services End -->

    <section class="py-4 overflow-hidden">
        <div class="container">
            <div class="row h-100">
                <div class="row">
                    <div class="col-lg-6">
                        <h2 class="section-title position-relative mb-3">Sản phẩm bán chạy</h2>
                    </div>
                </div>
                <div class="text-lg-right pb-2">
                    <a href="/product">
                        <h5 class="text-secondary">Xem tất cả ></h5>
                    </a>
                </div>
                <div class="col-12">
                    <div class="carousel slide" id="carouselPopularItems" data-bs-touch="false" data-bs-interval="false">
                        <div class="carousel-inner">
                            <div class="carousel-item active" data-bs-interval="10000">
                                <div class="row gx-3 h-100 align-items-center">
                                    <div class="col-sm-6 col-md-4 col-xl mb-5 h-100">
                                        <div class="card card-span h-100 rounded-3"><img class="img-fluid rounded-3 h-100"
                                                src="src/assets/img/product/pepsi.jpg" alt="..." />
                                            <div class="card-body ps-2">
                                                <h5 class="fw-bold text-1000 text-truncate mb-1">Pepsi</h5>
                                                <div><span class="text-warning me-2"><i
                                                            class="fas fa-map-marker-alt"></i></span><span
                                                        class="text-primary">Soft Drink</span></div><span
                                                    class="text-1000 fw-bold">15.000đ</span>
                                            </div>
                                        </div>
                                        <div class="d-grid gap-2 pt-2"><a class="btn btn-lg btn-danger" href="#!"
                                                role="button">Order now</a></div>
                                    </div>
                                    <div class="col-sm-6 col-md-4 col-xl mb-5 h-100">
                                        <div class="card card-span h-100 rounded-3"><img class="img-fluid rounded-3 h-100"
                                                src="src/assets/img/about.jpg" alt="..." />
                                            <div class="card-body ps-2">
                                                <h5 class="fw-bold text-1000 text-truncate mb-1">Coffee</h5>
                                                <div><span class="text-warning me-2"><i
                                                            class="fas fa-map-marker-alt"></i></span><span
                                                        class="text-primary">Coffee</span></div><span
                                                    class="text-1000 fw-bold">10.000đ</span>
                                            </div>
                                        </div>
                                        <div class="d-grid gap-2 pt-2"><a class="btn btn-lg btn-danger" href="#!"
                                                role="button">Order now</a></div>
                                    </div>
                                    <div class="col-sm-6 col-md-4 col-xl mb-5 h-100">
                                        <div class="card card-span h-100 rounded-3"><img class="img-fluid rounded-3 h-100"
                                                src="src/assets/img/product/7up.png" alt="..." />
                                            <div class="card-body ps-2">
                                                <h5 class="fw-bold text-1000 text-truncate mb-1">7 Up</h5>
                                                <div><span class="text-warning me-2"><i
                                                            class="fas fa-map-marker-alt"></i></span><span
                                                        class="text-primary">Soft Drink</span></div><span
                                                    class="text-1000 fw-bold">15.000đ</span>
                                            </div>
                                        </div>
                                        <div class="d-grid gap-2 pt-2"><a class="btn btn-lg btn-danger" href="#!"
                                                role="button">Order now</a></div>
                                    </div>
                                    <div class="col-sm-6 col-md-4 col-xl mb-5 h-100">
                                        <div class="card card-span h-100 rounded-3"><img class="img-fluid rounded-3 h-100"
                                                src="src/assets/img/product/white.jpg" alt="..." />
                                            <div class="card-body ps-2">
                                                <h5 class="fw-bold text-1000 text-truncate mb-1">White Pearls</h5>
                                                <div><span class="text-warning me-2"><i
                                                            class="fas fa-map-marker-alt"></i></span><span
                                                        class="text-primary">Topping</span></div><span
                                                    class="text-1000 fw-bold">5.000đ</span>
                                            </div>
                                        </div>
                                        <div class="d-grid gap-2 pt-2"><a class="btn btn-lg btn-danger" href="#!"
                                                role="button">Order now</a></div>
                                    </div>
                                    <div class="col-sm-6 col-md-4 col-xl mb-5 h-100">
                                        <div class="card card-span h-100 rounded-3"><img class="img-fluid rounded-3 h-100"
                                                src="src/assets/img/coca.jpg" alt="..." />
                                            <div class="card-body ps-2">
                                                <h5 class="fw-bold text-1000 text-truncate mb-1">Coca Cola</h5>
                                                <div><span class="text-warning me-2"><i
                                                            class="fas fa-map-marker-alt"></i></span><span
                                                        class="text-primary">Soft Drink</span></div><span
                                                    class="text-1000 fw-bold">15.000đ</span>
                                            </div>
                                        </div>
                                        <div class="d-grid gap-2 pt-2"><a class="btn btn-lg btn-danger" href="#!"
                                                role="button">Order now</a></div>
                                    </div>
                                </div>
                            </div>
                            <div class="carousel-item" data-bs-interval="5000">
                                <div class="row gx-3 h-100 align-items-center">
                                    <div class="col-sm-6 col-md-4 col-xl mb-5 h-100">
                                        <div class="card card-span h-100 rounded-3"><img class="img-fluid rounded-3 h-100"
                                                src="src/assets/img/siro.jpg" alt="..." />
                                            <div class="card-body ps-2">
                                                <h5 class="fw-bold text-1000 text-truncate mb-1">Strawberry Syrup</h5>
                                                <div><span class="text-warning me-2"><i
                                                            class="fas fa-map-marker-alt"></i></span><span
                                                        class="text-primary">Shaved Ice Syrup</span></div><span
                                                    class="text-1000 fw-bold">10.000đ</span>
                                            </div>
                                        </div>
                                        <div class="d-grid gap-2 pt-2"><a class="btn btn-lg btn-danger" href="#!"
                                                role="button">Order now</a></div>
                                    </div>
                                    <div class="col-sm-6 col-md-4 col-xl mb-5 h-100">
                                        <div class="card card-span h-100 rounded-3"><img class="img-fluid rounded-3 h-100"
                                                src="src/assets/img/mango.jpg" alt="..." />
                                            <div class="card-body ps-2">
                                                <h5 class="fw-bold text-1000 text-truncate mb-1">Yogurt Mango</h5>
                                                <div><span class="text-warning me-2"><i
                                                            class="fas fa-map-marker-alt"></i></span><span
                                                        class="text-primary">Shaved Ice Yogurt</span></div><span
                                                    class="text-1000 fw-bold">15.000đ</span>
                                            </div>
                                        </div>
                                        <div class="d-grid gap-2 pt-2"><a class="btn btn-lg btn-danger" href="#!"
                                                role="button">Order now</a></div>
                                    </div>
                                    <div class="col-sm-6 col-md-4 col-xl mb-5 h-100">
                                        <div class="card card-span h-100 rounded-3"><img class="img-fluid rounded-3 h-100"
                                                src="src/assets/img/product/cacao.jpg" alt="..." />
                                            <div class="card-body ps-2">
                                                <h5 class="fw-bold text-1000 text-truncate mb-1">CaCao Milk Coffee</h5>
                                                <div><span class="text-warning me-2"><i
                                                            class="fas fa-map-marker-alt"></i></span><span
                                                        class="text-primary">Coffee</span></div><span
                                                    class="text-1000 fw-bold">15.000đ</span>
                                            </div>
                                        </div>
                                        <div class="d-grid gap-2 pt-2"><a class="btn btn-lg btn-danger" href="#!"
                                                role="button">Order now</a></div>
                                    </div>
                                    <div class="col-sm-6 col-md-4 col-xl mb-5 h-100">
                                        <div class="card card-span h-100 rounded-3"><img class="img-fluid rounded-3 h-100"
                                                src="src/assets/img/service-3.jpg" alt="..." />
                                            <div class="card-body ps-2">
                                                <h5 class="fw-bold text-1000 text-truncate mb-1">Yogurt Strawberry</h5>
                                                <div><span class="text-warning me-2"><i
                                                            class="fas fa-map-marker-alt"></i></span><span
                                                        class="text-primary">Shaved Ice Yogurt</span></div><span
                                                    class="text-1000 fw-bold">15.000đ</span>
                                            </div>
                                        </div>
                                        <div class="d-grid gap-2 pt-2"><a class="btn btn-lg btn-danger" href="#!"
                                                role="button">Order now</a></div>
                                    </div>
                                    <div class="col-sm-6 col-md-4 col-xl mb-5 h-100">
                                        <div class="card card-span h-100 rounded-3"><img class="img-fluid rounded-3 h-100"
                                                src="src/assets/img/lemon.jpg" alt="..." />
                                            <div class="card-body ps-2">
                                                <h5 class="fw-bold text-1000 text-truncate mb-1">Lemon Syrup</h5>
                                                <div><span class="text-warning me-2"><i
                                                            class="fas fa-map-marker-alt"></i></span><span
                                                        class="text-primary">Shaved Ice Syrup</span></div><span
                                                    class="text-1000 fw-bold">10.000đ</span>
                                            </div>
                                        </div>
                                        <div class="d-grid gap-2 pt-2"><a class="btn btn-lg btn-danger" href="#!"
                                                role="button">Order now</a></div>
                                    </div>
                                </div>
                            </div>

                        </div>
                        <button class="carousel-control-prev-custom carousel-icon-custom" type="button"
                            data-bs-target="#carouselPopularItems" data-bs-slide="prev"><span
                                class="carousel-control-prev-custom-icon hover-top-shadow" aria-hidden="true"></span><span
                                class="visually-hidden">Previous</span></button>
                        <button class="carousel-control-next-custom carousel-icon-custom" type="button"
                            data-bs-target="#carouselPopularItems" data-bs-slide="next"><span
                                class="carousel-control-next-custom-icon hover-top-shadow" aria-hidden="true"></span><span
                                class="visually-hidden">Next </span></button>
                    </div>
                </div>
            </div>
        </div><!-- end of .container-->

    </section>
</template>
<script>
export default {
  mounted() {
    document.title = 'Trang chủ - Shop';
  }
}
</script>
