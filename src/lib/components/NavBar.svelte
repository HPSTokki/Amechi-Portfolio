<div class="drawer">
	<input id="nav-drawer" type="checkbox" class="drawer-toggle" />

	<div class="drawer-content flex flex-col">

		<!-- Terminal Navbar -->
		<div class="sticky top-0 z-50 border-b border-base-content/10 bg-base-300 backdrop-blur">

			<div class="mx-auto max-w-6xl flex items-center px-4 py-3">

				<!-- Mobile Menu -->
				<div class="flex-none lg:hidden">
					<label for="nav-drawer" class="btn btn-square btn-ghost">
						<svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" class="h-6 w-6 stroke-current">
							<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
								d="M4 6h16M4 12h16M4 18h16" />
						</svg>
					</label>
				</div>

				<!-- Logo -->
				<div class="flex-1 font-mono text-sm md:text-base">
					<span class="text-success">$</span>
					<span class="font-bold">rain@portfolio</span>
					<span class="opacity-60">:~</span>
				</div>

				<!-- Desktop Commands -->
				<div class="hidden lg:flex items-center gap-6 font-mono text-sm">

					<a href="#home" class="group transition">
						<span class="text-success">$</span>
						<span class="group-hover:text-primary"> cd home</span>
					</a>

					<a href="#about" class="group transition">
						<span class="text-success">$</span>
						<span class="group-hover:text-primary"> cat about</span>
					</a>

					<a href="#skills" class="group transition">
						<span class="text-success">$</span>
						<span class="group-hover:text-primary"> ls skills</span>
					</a>

					<a href="#projects" class="group transition">
						<span class="text-success">$</span>
						<span class="group-hover:text-primary"> ls projects</span>
					</a>

					<a href="#contact" class="group transition">
						<span class="text-success">$</span>
						<span class="group-hover:text-primary"> open contact</span>
					</a>

				</div>

			</div>
		</div>

	</div>

	<!-- Mobile Drawer -->
	<div class="drawer-side">
		<label for="nav-drawer" class="drawer-overlay"></label>

		<ul class="menu min-h-full w-72 bg-base-300 p-6 font-mono">

			<li class="mb-2 text-success">$ navigation</li>

			<li><a href="#home">cd home</a></li>
			<li><a href="#about">cat about</a></li>
			<li><a href="#skills">ls skills</a></li>
			<li><a href="#projects">ls projects</a></li>
			<li><a href="#contact">open contact</a></li>

		</ul>
	</div>
</div>
