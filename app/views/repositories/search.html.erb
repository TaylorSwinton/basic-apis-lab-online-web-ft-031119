class RepositoriesController < ApplicationController

  def search

  end

  def github_search
    client_id = 5caa9f801c829e507346
    client_secret = e748425b68a55f24d9d83b3425743e9540381dd9

    @resp = Faraday.get('https://api.github.com/search/repositories') do |req|
        req.params['client_id']= client_id
        req.params['client_secret']= client_secret
        req.params['q'] = params[:query]
    end

    body = JSON.parse(@resp.body)
    @results = body["items"]
    render 'search'
  end

end
