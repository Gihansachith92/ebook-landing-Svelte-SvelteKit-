<script>
  import chevronDown from "$assets/icons/chevron-down.svg";
</script>

<button class="container">
	<div class="question-and-answer">
		<p class="question mb-s">what usn hshh snsjsjsm?</p>
		<p class="answer">
			Lorem, ipsum dolor sit amet consectetur adipisicing elit. At architecto blanditiis corporis
			dicta deleniti accusamus, corrupti fugit! Tenetur corporis autem laboriosam rem. Veniam
			repellendus incidunt voluptatem laborum suscipit pariatur excepturi fugit cum, necessitatibus
			odit nisi asperiores sapiente ex ratione molestiae officia quaerat perferendis voluptate eos
			deleniti nostrum ipsa rem similique!
		</p>
	</div>
  <img src={chevronDown} alt="">
</button>

<style>
   .container{
		display: flex;
		justify-content: space-between;
		align-items: flex-start;
		padding: 12px 0;
		border-bottom: 1px solid grey;
		text-align: left;
	 }

	 .question-and-answer{
		padding-right: 150px;
		flex-grow: 1;
	 }

	 .answer{
		max-height: 0;
		overflow: hidden;
		opacity: 0;
		transition: max-height 0.3s ease-out, opacity 0.3s ease-out ;
	 }

	 button img{
		width: 24px;
		height: 24px;
		transition: transform 0.3s linear;
	 }

	 .question{
		font-weight: 600;
	 }

	 .container-expanded img{
		transform: rotate(180deg);
	 }

	 .container-expanded .answer{
		max-height: unset;
		opacity: 1;
	 }

</style>
