<template>
  <Page class="page">
    <ActionBar class="action-bar" title="Home"/>

    <StackLayout>
      <Button class="btn btn-primary" @tap="$router.push('/counter')">Counter</Button>
      <Button class="btn btn-primary" @tap="$router.push('/ajax-list-view')">Ajax List View</Button>
      <Button class="btn btn-primary" @tap="$router.push('/store-login')">Store Login</Button>
      <Button class="btn btn-primary" @tap="$router.push('/star-rating')">Star Rating</Button>
      <Button class="btn btn-primary" @tap="$router.push('/camera')">Camera</Button>
      <Button class="btn btn-primary" @tap="$router.push('/hello')">Hello World</Button>
    </StackLayout>

  </Page>
</template>
