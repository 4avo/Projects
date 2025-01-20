<script>
  // Your register logic here
</script>

<div class="bg-gray-800 text-white min-h-screen flex items-center justify-center">
  <div class="p-6 bg-gray-900 rounded-lg shadow-lg">
    <h2 class="text-3xl font-bold text-center text-green-400 mb-4">Register</h2>
    <form action="#" method="POST">
      <label for="username" class="block text-lg">Username</label>
      <input type="text" id="username" name="username" class="w-full p-2 mb-4 bg-gray-700 text-white rounded" />

      <label for="password" class="block text-lg">Password</label>
      <input type="password" id="password" name="password" class="w-full p-2 mb-4 bg-gray-700 text-white rounded" />

      <button type="submit" class="w-full py-3 bg-gradient-to-r from-green-400 to-blue-500 text-white font-semibold rounded-lg">
        Register
      </button>
    </form>

    <!-- Link to login page -->
    <p class="mt-4 text-center text-gray-400">
      Already have an account? 
      <a href="/login" class="text-green-400 hover:underline">Log in</a>
    </p>
  </div>
</div>
