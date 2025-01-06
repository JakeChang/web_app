<template>

	<div class="bg-gradient-to-b from-gray-900 to-gray-800 text-white">

		<section class="min-h-screen flex items-center justify-center relative overflow-hidden">
			<div class="absolute w-full h-full bg-gradient-to-r from-blue-500/10 to-purple-500/10 animate-pulse"></div>

			<div class="container mx-auto px-4 text-center relative z-10">
				<img src="./assets/logo.png" alt="App Logo" class="w-32 h-32 mx-auto mb-4">
				<h1
					class="text-6xl md:text-8xl font-bold mb-6 bg-gradient-to-r from-blue-400 to-purple-600 text-transparent bg-clip-text">
					Render Clean
				</h1>
				<p class="text-xl md:text-2xl text-gray-300 mb-8">
					安全可靠的刪除 Final Cut Pro 暫存檔案
				</p>
				<img src="./assets/main.png" width="900" alt="App Screenshot"
					class="rounded-2xl mx-auto transform hover:scale-105 transition-transform duration-500 hover:shadow-purple-500/50">
			</div>
		</section>

		<!-- 特色功能 -->
		<section class="py-20 bg-gray-800">
			<div class="container mx-auto px-4">
				<h2 class="text-4xl font-bold text-center mb-16">功能</h2>

				<div class="grid grid-cols-1 md:grid-cols-3 gap-8">
					<!-- 功能卡片 1 -->
					<div
						class="bg-gray-700 rounded-xl p-6 hover:bg-gray-600 transition-all duration-300 transform hover:-translate-y-2">
						<div class="text-blue-400 text-4xl mb-4">
							<i class="fas fa-bolt"></i>
						</div>
						<h3 class="text-xl font-bold mb-4">計算檔案大小</h3>
						<p class="text-gray-300">計算所使用的暫存檔案大小</p>
					</div>

					<!-- 功能卡片 2 -->
					<div
						class="bg-gray-700 rounded-xl p-6 hover:bg-gray-600 transition-all duration-300 transform hover:-translate-y-2">
						<div class="text-purple-400 text-4xl mb-4">
							<i class="fas fa-shield-alt"></i>
						</div>
						<h3 class="text-xl font-bold mb-4">安全可靠</h3>
						<p class="text-gray-300">安全可靠的刪除暫存檔案</p>
					</div>

					<!-- 功能卡片 3 -->
					<div
						class="bg-gray-700 rounded-xl p-6 hover:bg-gray-600 transition-all duration-300 transform hover:-translate-y-2">
						<div class="text-green-400 text-4xl mb-4">
							<i class="fas fa-sync"></i>
						</div>
						<h3 class="text-xl font-bold mb-4">刪除暫存檔案</h3>
						<p class="text-gray-300">刪除所使用的暫存檔案</p>
					</div>
				</div>
			</div>
		</section>

		<!-- 價格區段 -->
		<section class="py-20 bg-gray-900">
			<div class="container mx-auto px-4">
				<div class="max-w-3xl mx-auto bg-gradient-to-r from-blue-600 to-purple-600 rounded-2xl p-1">
					<div class="bg-gray-800 rounded-xl p-8 text-center">
						<h3 class="text-2xl font-bold mb-4"></h3>
						<div class="text-5xl font-bold mb-6">免費</div>
						<button
							class="bg-gradient-to-r from-blue-500 to-purple-500 text-white px-8 py-3 rounded-lg hover:opacity-90 transition-opacity">
							<a href="/RenderClean.zip">立即下載</a>
						</button>
					</div>
				</div>
			</div>
		</section>

		<!-- 頁尾 -->
		<footer class="py-8 bg-gray-900 border-t border-gray-800">
			<div class="container mx-auto px-4 text-center text-gray-400">
				<p>&copy; 2025 傑克老師 Studio. All rights reserved.</p>
			</div>
		</footer>

	</div>
</template>

<script>
export default {
	name: 'App',
}
</script>
