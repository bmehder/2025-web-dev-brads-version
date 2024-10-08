<form>
	<div class="flow max-width-sm">
		<div class="input-group">
			<label for="first-name">First Name <span class="required">*</span></label>
			<input
				type="text"
				id="first-name"
				name="first-name"
				placeholder="Enter first name..."
				required
			/>
		</div>
		<div class="input-group">
			<label for="last-name">Last Name <span class="required">*</span></label>
			<input
				type="text"
				id="last-name"
				name="last-name"
				placeholder="Enter last name..."
				required
			/>
		</div>
		<div class="input-group">
			<label for="email">Email <span class="required">*</span></label>
			<input
				type="email"
				id="email"
				name="email"
				placeholder="Enter email address..."
				required
			/>
		</div>
		<div class="input-group">
			<label for="phone">Phone <span class="normal">(optional)</span></label>
			<input
				type="tel"
				id="phone"
				name="phone"
				placeholder="Enter phone number..."
			/>
		</div>
		<div class="input-group">
			<label for="message">Message <span class="required">*</span></label>
			<textarea
				name="message"
				id="message"
				placeholder="Enter your message..."
				minlength="10"
				required
			></textarea>
		</div>
		<div>
			<button class="bg-pink-600 white">Send Message</button>
		</div>
	</div>
</form>

<style>
	button:hover {
		background-color: var(--blue-900);
	}
</style>
