<script lang="ts">
	import '../app.css';
</script>

<svelte:head>
	<link rel="preconnect" href="https://fonts.googleapis.com" />
	<link rel="preconnect" href="https://fonts.gstatic.com" />
	<link
		href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@800;400&family=Roboto:wght@500&display=swap"
	/>
</svelte:head>

<section>
	<div class="container" id="header">
		<h1>Realign 2023</h1>
		<p>
			Yeah, yeah, New Year’s Resolutions. With potential peer pressure and committing to a scheduled
			time, you’re far more likely to get these done.
		</p>

		<!-- <form>
			<input type="email" name="email" id="email" placeholder="youremail@somewhere.com" required />
			<input type="submit" value="Submit" />
		</form> -->

		<h2>Coming soon!</h2>
	</div>
</section>

<section>
	<div class="container">
		<h2>This is for you if...</h2>

		<p>
			This is for you if you plan to majorly upskill, change jobs, start new ventures, create
			content, and have an idea of your career direction.
		</p>
		<p>
			Realign helps you to keep your online presence updated year through small reminders and
			manageable weekly task loads.
		</p>
	</div>

	<div class="container">
		<h2>Time commitment</h2>
		<p>
			The amount of time spent weekly is variable depending on the task - an evening, maybe a day of
			your weekend. Alternatively, spread the tasks throughout the week.
		</p>
	</div>
	<div class="container">
		<h2>Weekly task list</h2>
		<p>Summaries will be replaced with the full prompts on Mondays.</p>

		<p>
			If you're new and don't have any existing content, we'll link to templates and tutorials to
			get you start quickly if you're in our <a href="https://ladyofcode.com/community"
				>community Discord</a
			>. This shouldn't be overwhelming!
		</p>

		<p>
			Full instructions, shortcuts, and tips, will be posted each week in our <a
				href="https://ladyofcode.com/community">community Discord</a
			>
			announcements channel in addition to the prompts here. Add yourself to the Realign role to get
			notifications!
		</p>
	</div>
</section>

<footer>
	<p>
		Made with far too much love by <a href="https://ladyofcode.com">Tabs</a>. All rights reserved.
		Yes, all of them.
	</p>
</footer>

<style>
	section {
		/* background-color: cadetblue; */
		min-height: 70vh;
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		max-width: 1024px;
		margin: 0 auto;
		margin-bottom: 64px;
	}

	footer {
		background-color: #000000;
		color: #ffffff;
		width: 100%;
		padding: 12px 0px;
	}

	footer > p {
		max-width: 1024px;
		margin: 0 auto;
		text-align: center;
	}

	a {
		color: hsl(173, 90%, 30%);
		text-decoration: none;
	}

	h1 {
		font-family: 'Playfair Display', serif;
		font-weight: 800;
		font-size: 4.8em;
		margin-bottom: 1em;
	}

	h2 {
		font-family: 'Playfair Display', serif;
		font-size: 1.6em;
		padding: 12px;
		margin-top: 1em;
		margin-bottom: 1em;
		font-weight: 400;
	}

	p
	/* input  */
	{
		font-family: 'Roboto', sans-serif;
		font-weight: 500;
	}

	p {
		font-size: 1.2em;
		margin-top: 1em;
	}

	.container {
		max-width: 100%;
		padding: 20px;
	}

	#header {
		background-color: #ffffff;
		border: solid 5px rgb(32, 32, 32);
		border-radius: 255px 16px 225px 16px/16px 225px 16px 255px;
		margin: 12px;
	}

	#header > p {
		font-size: 1.2em;
		margin-bottom: 2em;
	}

	/* form input {
		box-sizing: border-box;
		padding: 12px;
		border-radius: 255px 15px 225px 15px/15px 225px 15px 255px;
		border: solid 2px hsl(0, 0%, 13%);
		margin-top: 20px;
		min-width: 100%;
	}

	form input[type='email'] {
		padding: 24px 24px;
	}

	::placeholder {
		color: hsl(0, 0%, 80%) f;
	}

	form input[type='submit'] {
		color: hsl(0, 0%, 100%);
		background-color: hsl(0, 0%, 0%);
	} */

	h2 {
		border-radius: 255px 15px 225px 15px/15px 225px 15px 255px;
		border: solid 2px hsl(0, 0%, 16%);
		background-color: hsl(0, 0%, 16%);
		color: #ffffff;
	}

	@media (min-width: 480px) {
		h1 {
			font-size: 6.4em;
		}

		h2 {
			font-size: 2.4em;
			max-width: 50%;
		}

		.container {
			padding: 80px;
		}

		/* form input {
			padding: 24px;
		}

		form input[type='email'] {
			min-width: 320px;
		}

		form input[type='submit'] {
			min-width: 120px;
		} */
	}
</style>
