<script>

</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="150" height="150" />
    <div>
      <h1>Welcome</h1>
    </div>

    <nav>
      <ul>
        <li><a href="#">Home</a></li>
      </ul>

      <form>
        <input type="search" name="q" placeholder="Search a movie" />
        <input type="submit" value="Click" />
      </form>
    </nav>
  </header>

  <main>
    <label for="movie recommend">Movie of This Month : </label>
    <select id="title">
      <option value="">--Please choose a title--</option>
      <option value="Avatar">Avatar2</option>
      <option value="RRR">RRR</option>
      <option value="기생충">기생충</option>
    </select>
  </main>
</template>

<style scoped>
header {
  line-height: 2;
  max-height: 100vh;
}
</style>
