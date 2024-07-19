<template>
  <div>
    <header>
			<nav>
				<NuxtLink to="/">Nuxt Dojo</NuxtLink>
				<ul>
					<li><NuxtLink to="/">Home</NuxtLink></li>
					<li><NuxtLink to="/about">About</NuxtLink></li>
					<li><NuxtLink to="/products">Products</NuxtLink></li>
				</ul>
			</nav>
		</header>
    <h2>About</h2>
    <p>
      Lorem ipsum, dolor sit amet consectetur adipisicing elit. Animi ut omnis
      perspiciatis quibusdam. Ex, exercitationem aperiam. Rerum non dicta qui
      nesciunt quae. Veritatis, aliquid similique? Facere repellendus neque
      beatae nisi.
    </p>
    <p>
      Lorem, ipsum dolor sit amet consectetur adipisicing elit. Consequatur
      facilis quaerat commodi quos quas ea quo, optio enim ad perferendis ipsum
      aliquam porro cumque necessitatibus dolore numquam quae voluptatibus rem.
    </p>
  </div>
</template>

<script setup></script>

<style scoped>
h2 {
  margin-bottom: 20px;
  font-size: 36px;
}
p {
  margin: 20px 0;
}
</style>
