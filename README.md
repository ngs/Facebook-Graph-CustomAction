just tasting...

    use Facebook::Graph;
    use Facebook::Graph::Publish::Ngsdevorg::Listen;

    my $fb = Facebook::Graph->new;

    $fb->add_listen
      ->set_music_uri( 'http://samples.ogp.me/201651986570895' )
      ->set_message( 'Awesome music!' )
      ->publish;



