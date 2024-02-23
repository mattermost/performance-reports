### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| UserStore.GetMany | avg | 2ms | 5ms | 3ms | 198.61
| ChannelStore.UpdateSidebarCategories | avg | 28ms | 43ms | 15ms | 52.94
| LinkMetadataStore.Save | avg | 4ms | 6ms | 2ms | 46.64
| ChannelStore.GetTeamChannels | avg | 36ms | 48ms | 12ms | 33.14
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| UserStore.GetMany | p99 | 5ms | 94ms | 89ms | 1797.98
| ChannelStore.UpdateSidebarCategories | p99 | 50ms | 447ms | 397ms | 797.91
| ChannelStore.GetTeamChannels | p99 | 50ms | 239ms | 189ms | 379.90
| LinkMetadataStore.Save | p99 | 10ms | 41ms | 31ms | 318.34
| BotStore.Get | p99 | 92ms | 224ms | 132ms | 144.26
| ThreadStore.MarkAllAsReadByChannels | p99 | 10ms | 21ms | 11ms | 114.19
| UserStore.Update | p99 | 10ms | 19ms | 9ms | 90.45
| FileInfoStore.AttachToPost | p99 | 15ms | 22ms | 7ms | 47.68
| PostPriorityStore.GetForPost | p99 | 142ms | 187ms | 45ms | 31.69
| PostStore.Update | p99 | 44ms | 57ms | 13ms | 29.38
| StatusStore.SaveOrUpdate | p99 | 451ms | 459ms | 8ms | 1.77
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | avg | 1.154s | 0s | -1.154s | -100.04
| ProductNoticesStore.ClearOldNotices | avg | 2ms | 0s | -2ms | -91.09
| PostStore.GetPostReminderMetadata | avg | 4ms | 1ms | -3ms | -81.79
| RoleStore.ChannelHigherScopedPermissions | avg | 4ms | 1ms | -3ms | -79.28
| UserStore.Get | avg | 3ms | 1ms | -2ms | -77.35
| SessionStore.GetSessionsExpired | avg | 13ms | 3ms | -10ms | -76.68
| JobStore.Get | avg | 6ms | 2ms | -4ms | -67.37
| PostStore.GetPostsAfter | avg | 8ms | 3ms | -5ms | -64.08
| StatusStore.GetByIds | avg | 3ms | 1ms | -2ms | -63.26
| ChannelStore.GetGuestCount | avg | 32ms | 13ms | -19ms | -60.07
| UserStore.GetUnreadCount | avg | 9ms | 4ms | -5ms | -58.67
| PostPriorityStore.GetForPosts | avg | 9ms | 4ms | -5ms | -57.27
| PostAcknowledgementStore.GetForPost | avg | 9ms | 4ms | -5ms | -56.33
| EmojiStore.GetByName | avg | 5ms | 2ms | -3ms | -56.29
| StatusStore.Get | avg | 13ms | 6ms | -7ms | -55.81
| PreferenceStore.GetAll | avg | 24ms | 11ms | -13ms | -55.26
| ChannelStore.GetPinnedPostCount | avg | 11ms | 5ms | -6ms | -55.22
| UserStore.IsEmpty | avg | 11ms | 5ms | -6ms | -54.70
| ChannelStore.CreateDirectChannel | avg | 46ms | 21ms | -25ms | -54.67
| GroupStore.GetByName | avg | 17ms | 8ms | -9ms | -53.31
| UserTermsOfServiceStore.GetByUser | avg | 19ms | 9ms | -10ms | -52.27
| ChannelStore.SearchGroupChannels | avg | 6ms | 3ms | -3ms | -51.99
| TeamStore.GetTeamsForUser | avg | 17ms | 8ms | -9ms | -51.48
| ChannelStore.GetMembersForUser | avg | 10ms | 5ms | -5ms | -51.45
| ChannelStore.GetMemberLastViewedAt | avg | 16ms | 8ms | -8ms | -51.09
| PostStore.GetEtag | avg | 14ms | 7ms | -7ms | -50.84
| TeamStore.GetChannelUnreadsForAllTeams | avg | 16ms | 8ms | -8ms | -49.99
| JobStore.GetCountByStatusAndType | avg | 8ms | 4ms | -4ms | -49.67
| ChannelStore.GetChannels | avg | 10ms | 5ms | -5ms | -49.15
| UserStore.GetForLogin | avg | 18ms | 9ms | -9ms | -48.68
| GroupStore.AdminRoleGroupsForSyncableMember | avg | 14ms | 7ms | -7ms | -48.28
| UserStore.GetAllProfiles | avg | 17ms | 9ms | -8ms | -48.24
| TeamStore.GetTeamsByUserId | avg | 19ms | 10ms | -9ms | -47.97
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 55ms | 29ms | -26ms | -47.65
| PostAcknowledgementStore.GetForPosts | avg | 8ms | 4ms | -4ms | -47.54
| PostStore.GetPosts | avg | 20ms | 11ms | -9ms | -46.09
| JobStore.GetNewestJobByStatusesAndType | avg | 9ms | 5ms | -4ms | -46.05
| TeamStore.GetAllPage | avg | 17ms | 9ms | -8ms | -45.89
| ChannelStore.GetByName | avg | 15ms | 8ms | -7ms | -45.24
| ThreadStore.GetThreadsForUser | avg | 7ms | 4ms | -3ms | -44.35
| ThreadStore.GetTotalUnreadThreads | avg | 14ms | 8ms | -6ms | -44.20
| SessionStore.Get | avg | 21ms | 12ms | -9ms | -43.69
| ThreadStore.GetTotalThreads | avg | 14ms | 8ms | -6ms | -43.02
| ThreadStore.GetTeamsUnreadForUser | avg | 16ms | 9ms | -7ms | -42.73
| ThreadStore.GetTotalUnreadUrgentMentions | avg | 14ms | 8ms | -6ms | -42.09
| ThreadStore.GetTotalUnreadMentions | avg | 12ms | 7ms | -5ms | -40.33
| GroupStore.GetGroups | avg | 10ms | 6ms | -4ms | -40.08
| SessionStore.Save | avg | 23ms | 14ms | -9ms | -39.92
| ThreadStore.GetMembershipForUser | avg | 5ms | 3ms | -2ms | -39.70
| ChannelStore.SaveMember | avg | 94ms | 57ms | -37ms | -39.37
| PostPersistentNotificationStore.GetSingle | avg | 5ms | 3ms | -2ms | -39.18
| PreferenceStore.Get | avg | 5ms | 3ms | -2ms | -38.98
| UserStore.GetByUsername | avg | 5ms | 3ms | -2ms | -38.13
| ChannelStore.GetMemberCount | avg | 263ms | 163ms | -100ms | -38.04
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | avg | 5ms | 3ms | -2ms | -37.93
| ChannelStore.GetFileCount | avg | 8ms | 5ms | -3ms | -37.79
| UserStore.GetProfilesByUsernames | avg | 5ms | 3ms | -2ms | -37.49
| PostStore.GetPostsBefore | avg | 8ms | 5ms | -3ms | -37.01
| ChannelStore.Save | avg | 16ms | 10ms | -6ms | -36.70
| JobStore.GetAllByStatus | avg | 6ms | 4ms | -2ms | -34.25
| ChannelStore.GetChannelsByUser | avg | 46ms | 32ms | -14ms | -30.60
| PostStore.GetPostsSince | avg | 14ms | 10ms | -4ms | -29.60
| ThreadStore.GetThreadForUser | avg | 7ms | 5ms | -2ms | -29.52
| ChannelStore.Get | avg | 10ms | 7ms | -3ms | -29.37
| WebhookStore.GetOutgoingByTeam | avg | 7ms | 5ms | -2ms | -27.98
| PostPriorityStore.GetForPost | avg | 7ms | 5ms | -2ms | -27.86
| PostStore.Get | avg | 8ms | 6ms | -2ms | -26.41
| UserStore.Count | avg | 123ms | 91ms | -32ms | -26.03
| TeamStore.GetByName | avg | 9ms | 7ms | -2ms | -23.31
| ChannelStore.GetPublicChannelsForTeam | avg | 13ms | 10ms | -3ms | -22.47
| UserStore.GetAllProfilesInChannel | avg | 624ms | 494ms | -130ms | -20.85
| ChannelStore.CreateInitialSidebarCategories | avg | 34ms | 27ms | -7ms | -20.78
| ChannelStore.GetAllChannelMemberIdsByChannelId | avg | 16ms | 13ms | -3ms | -19.09
| ChannelStore.AutocompleteInTeamForSearch | avg | 149ms | 124ms | -25ms | -16.79
| PostStore.SearchPostsForUser | avg | 97ms | 82ms | -15ms | -15.49
| UserStore.Search | avg | 105ms | 93ms | -12ms | -11.47
| UserStore.AutocompleteUsersInChannel | avg | 231ms | 211ms | -20ms | -8.67
| TeamStore.SaveMember | avg | 111ms | 104ms | -7ms | -6.28
| ChannelStore.Autocomplete | avg | 1.61s | 1.568s | -42ms | -2.61
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ProductNoticesStore.ClearOldNotices | p99 | 5ms | 0s | -5ms | -100.99
| PostStore.AnalyticsPostCount | p99 | 2.485s | 0s | -2.485s | -99.99
| RoleStore.ChannelHigherScopedPermissions | p99 | 84ms | 5ms | -79ms | -94.61
| StatusStore.GetByIds | p99 | 126ms | 10ms | -116ms | -92.43
| PostStore.GetPostReminderMetadata | p99 | 46ms | 5ms | -41ms | -89.78
| UserAccessTokenStore.GetByToken | p99 | 44ms | 5ms | -39ms | -88.14
| JobStore.Get | p99 | 180ms | 23ms | -157ms | -87.47
| UserStore.Get | p99 | 48ms | 6ms | -42ms | -87.31
| ChannelStore.Save | p99 | 213ms | 35ms | -178ms | -83.47
| PostStore.GetPostsAfter | p99 | 211ms | 43ms | -168ms | -79.62
| ReactionStore.GetForPost | p99 | 88ms | 18ms | -70ms | -79.28
| FileInfoStore.GetForPost | p99 | 90ms | 20ms | -70ms | -78.01
| PostPersistentNotificationStore.DeleteExpired | p99 | 21ms | 5ms | -16ms | -77.48
| SessionStore.GetSessionsExpired | p99 | 97ms | 24ms | -73ms | -75.65
| ChannelStore.GetPublicChannelsForTeam | p99 | 107ms | 30ms | -77ms | -71.86
| UserStore.GetUnreadCount | p99 | 280ms | 84ms | -196ms | -70.02
| ChannelStore.CreateDirectChannel | p99 | 510ms | 157ms | -353ms | -69.22
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 249ms | 91ms | -158ms | -63.33
| JobStore.GetNewestJobByStatusesAndType | p99 | 255ms | 100ms | -155ms | -60.78
| JobStore.GetCountByStatusAndType | p99 | 213ms | 86ms | -127ms | -59.55
| PostStore.SetPostReminder | p99 | 24ms | 10ms | -14ms | -58.82
| EmojiStore.GetByName | p99 | 160ms | 67ms | -93ms | -58.11
| PostPriorityStore.GetForPosts | p99 | 227ms | 96ms | -131ms | -57.63
| ChannelStore.GetMemberForPost | p99 | 63ms | 27ms | -36ms | -57.02
| PostAcknowledgementStore.GetForPosts | p99 | 218ms | 94ms | -124ms | -56.84
| JobStore.UpdateOptimistically | p99 | 21ms | 9ms | -12ms | -55.88
| FileInfoStore.Get | p99 | 59ms | 27ms | -32ms | -54.48
| PostStore.GetPostsBefore | p99 | 198ms | 91ms | -107ms | -54.13
| UserStore.IsEmpty | p99 | 204ms | 94ms | -110ms | -53.89
| ChannelStore.GetFileCount | p99 | 176ms | 82ms | -94ms | -53.50
| PreferenceStore.DeleteCategoryAndName | p99 | 10ms | 5ms | -5ms | -52.08
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 164ms | 79ms | -85ms | -51.71
| ChannelStore.SearchGroupChannels | p99 | 175ms | 85ms | -90ms | -51.43
| UserStore.GetProfileByIds | p99 | 24ms | 12ms | -12ms | -50.90
| ThreadStore.GetThreadsForUser | p99 | 191ms | 95ms | -96ms | -50.25
| PluginStore.List | p99 | 80ms | 40ms | -40ms | -50.00
| ChannelStore.GetSidebarCategory | p99 | 20ms | 10ms | -10ms | -49.99
| WebhookStore.GetOutgoingByTeam | p99 | 177ms | 89ms | -88ms | -49.71
| PreferenceStore.Get | p99 | 158ms | 81ms | -77ms | -48.59
| PostStore.GetPostsSince | p99 | 211ms | 111ms | -100ms | -47.44
| UserStore.GetProfilesByUsernames | p99 | 152ms | 80ms | -72ms | -47.40
| PostStore.Get | p99 | 175ms | 93ms | -82ms | -46.76
| UserStore.Count | p99 | 465ms | 248ms | -217ms | -46.67
| PostAcknowledgementStore.GetForPost | p99 | 178ms | 96ms | -82ms | -46.07
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 87ms | 49ms | -38ms | -43.73
| ChannelStore.GetGuestCount | p99 | 427ms | 241ms | -186ms | -43.60
| ThreadStore.GetThreadForUser | p99 | 175ms | 99ms | -76ms | -43.43
| ChannelStore.GetChannelsByUser | p99 | 409ms | 246ms | -163ms | -39.88
| PostPersistentNotificationStore.GetSingle | p99 | 161ms | 97ms | -64ms | -39.75
| ChannelStore.GetPinnedPostCount | p99 | 237ms | 147ms | -90ms | -37.95
| JobStore.GetAllByStatus | p99 | 187ms | 117ms | -70ms | -37.43
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 768ms | 483ms | -285ms | -37.09
| ThreadStore.GetThreadUnreadReplyCount | p99 | 63ms | 40ms | -23ms | -36.72
| ThreadStore.GetMembershipForUser | p99 | 141ms | 92ms | -49ms | -34.68
| ThreadStore.GetThreadFollowers | p99 | 162ms | 106ms | -56ms | -34.59
| ChannelStore.AutocompleteInTeamForSearch | p99 | 982ms | 646ms | -336ms | -34.21
| UserStore.Search | p99 | 607ms | 403ms | -204ms | -33.61
| ChannelStore.GetMembersForUser | p99 | 216ms | 144ms | -72ms | -33.35
| PostStore.SearchPostsForUser | p99 | 2.071s | 1.386s | -685ms | -33.07
| TeamStore.GetByName | p99 | 263ms | 177ms | -86ms | -32.66
| ChannelStore.GetChannels | p99 | 222ms | 151ms | -71ms | -32.02
| TeamStore.Get | p99 | 128ms | 87ms | -41ms | -31.97
| UserStore.GetAllProfiles | p99 | 222ms | 151ms | -71ms | -31.94
| TeamStore.SaveMember | p99 | 408ms | 296ms | -112ms | -27.45
| GroupStore.GetGroups | p99 | 223ms | 165ms | -58ms | -26.02
| ChannelStore.GetByName | p99 | 239ms | 177ms | -62ms | -25.92
| ChannelStore.SaveMember | p99 | 964ms | 735ms | -229ms | -23.75
| ChannelStore.Autocomplete | p99 | 8.383s | 6.45s | -1.933s | -23.06
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 236ms | 183ms | -53ms | -22.47
| ChannelStore.GetMemberLastViewedAt | p99 | 242ms | 188ms | -54ms | -22.30
| UserStore.GetForLogin | p99 | 248ms | 195ms | -53ms | -21.34
| PostStore.GetEtag | p99 | 245ms | 193ms | -52ms | -21.27
| StatusStore.Get | p99 | 218ms | 172ms | -46ms | -21.13
| GroupStore.GetByName | p99 | 237ms | 188ms | -49ms | -20.65
| PostStore.GetPostsByThread | p99 | 54ms | 43ms | -11ms | -20.25
| ThreadStore.GetTeamsUnreadForUser | p99 | 244ms | 198ms | -46ms | -18.84
| TeamStore.GetAllPage | p99 | 244ms | 198ms | -46ms | -18.82
| ChannelStore.Get | p99 | 233ms | 190ms | -43ms | -18.45
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 239ms | 195ms | -44ms | -18.41
| TeamStore.GetTeamsForUser | p99 | 240ms | 197ms | -43ms | -17.95
| PostStore.GetSingle | p99 | 79ms | 65ms | -14ms | -17.72
| UserTermsOfServiceStore.GetByUser | p99 | 248ms | 205ms | -43ms | -17.33
| PostStore.GetPosts | p99 | 244ms | 202ms | -42ms | -17.21
| ClusterDiscoveryStore.SetLastPingAt | p99 | 12ms | 10ms | -2ms | -17.17
| TeamStore.GetTeamsByUserId | p99 | 247ms | 206ms | -41ms | -16.60
| PreferenceStore.GetAll | p99 | 249ms | 210ms | -39ms | -15.63
| ThreadStore.GetTotalUnreadMentions | p99 | 229ms | 194ms | -35ms | -15.28
| SessionStore.Save | p99 | 243ms | 206ms | -37ms | -15.22
| SessionStore.Get | p99 | 247ms | 210ms | -37ms | -14.98
| UserStore.Save | p99 | 163ms | 140ms | -23ms | -14.13
| ThreadStore.GetTotalUnreadThreads | p99 | 231ms | 199ms | -32ms | -13.84
| ProductNoticesStore.View | p99 | 145ms | 125ms | -20ms | -13.75
| ThreadStore.GetTotalThreads | p99 | 234ms | 202ms | -32ms | -13.65
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 235ms | 204ms | -31ms | -13.21
| ChannelStore.GetMemberCount | p99 | 981ms | 855ms | -126ms | -12.85
| UserStore.GetByUsername | p99 | 103ms | 91ms | -12ms | -11.65
| ChannelStore.GetMember | p99 | 18ms | 16ms | -2ms | -11.30
| LinkMetadataStore.Get | p99 | 80ms | 71ms | -9ms | -11.26
| ChannelStore.GetAllChannelMembersForUser | p99 | 27ms | 24ms | -3ms | -11.14
| UserStore.AutocompleteUsersInChannel | p99 | 949ms | 849ms | -100ms | -10.53
| ChannelStore.CreateInitialSidebarCategories | p99 | 247ms | 223ms | -24ms | -9.70
| PostStore.GetPostReminders | p99 | 24ms | 22ms | -2ms | -8.43
| UserStore.GetAllProfilesInChannel | p99 | 2.429s | 2.245s | -184ms | -7.57
| PreferenceStore.Save | p99 | 43ms | 41ms | -2ms | -4.64
| ChannelStore.GetChannelUnread | p99 | 217ms | 209ms | -8ms | -3.69
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| patchPost | avg | 34ms | 54ms | 20ms | 58.72
| updateCategoriesForTeamForUser | avg | 39ms | 53ms | 14ms | 36.17
| createChannel | avg | 36ms | 49ms | 13ms | 35.80
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateCategoriesForTeamForUser | p99 | 92ms | 447ms | 355ms | 387.23
| createChannel | p99 | 50ms | 239ms | 189ms | 379.90
| patchPost | p99 | 540ms | 1.21s | 670ms | 124.07
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannel | avg | 23ms | 3ms | -20ms | -87.60
| setPostReminder | avg | 46ms | 11ms | -35ms | -76.38
| getTeamMembersForUser | avg | 20ms | 9ms | -11ms | -56.30
| saveReaction | avg | 20ms | 9ms | -11ms | -56.28
| getAllTeams | avg | 19ms | 9ms | -10ms | -53.17
| searchGroupChannels | avg | 6ms | 3ms | -3ms | -51.47
| getPreferences | avg | 24ms | 12ms | -12ms | -49.90
| getUser | avg | 22ms | 11ms | -11ms | -49.26
| getTeamsUnreadForUser | avg | 25ms | 13ms | -12ms | -47.89
| getTeamsForUser | avg | 19ms | 10ms | -9ms | -47.69
| getCategoriesForTeamForUser | avg | 55ms | 29ms | -26ms | -47.37
| getPostsForChannelAroundLastUnread | avg | 87ms | 48ms | -39ms | -45.07
| getThreadsForUser | avg | 9ms | 5ms | -4ms | -43.24
| getChannelMember | avg | 28ms | 16ms | -12ms | -42.79
| getUsers | avg | 19ms | 11ms | -8ms | -42.54
| getChannelsForTeamForUser | avg | 12ms | 7ms | -5ms | -41.63
| getChannelStats | avg | 32ms | 19ms | -13ms | -40.69
| getPostThread | avg | 15ms | 9ms | -6ms | -39.30
| getChannelMembersForTeamForUser | avg | 10ms | 6ms | -4ms | -38.69
| getUsersByNames | avg | 5ms | 3ms | -2ms | -36.61
| getPostsForChannel | avg | 42ms | 27ms | -15ms | -36.13
| viewChannel | avg | 18ms | 13ms | -5ms | -28.44
| getPublicChannelsForTeam | avg | 15ms | 11ms | -4ms | -27.49
| getChannelsForUser | avg | 47ms | 37ms | -10ms | -21.27
| addTeamMember | avg | 1.75s | 1.382s | -368ms | -21.02
| login | avg | 96ms | 76ms | -20ms | -20.80
| addChannelMember | avg | 226ms | 183ms | -43ms | -19.06
| searchPostsInTeam | avg | 105ms | 86ms | -19ms | -18.07
| createDirectChannel | avg | 227ms | 188ms | -39ms | -17.20
| createPost | avg | 507ms | 421ms | -86ms | -16.98
| autocompleteChannelsForTeamForSearch | avg | 149ms | 124ms | -25ms | -16.78
| createGroupChannel | avg | 318ms | 275ms | -43ms | -13.53
| autocompleteUsers | avg | 186ms | 161ms | -25ms | -13.47
| createUser | avg | 120ms | 105ms | -15ms | -12.45
| searchUsers | avg | 105ms | 94ms | -11ms | -10.45
| updateReadStateThreadByUser | avg | 30ms | 27ms | -3ms | -9.85
| getProfileImage | avg | 100ms | 93ms | -7ms | -7.02
| getFileThumbnail | avg | 33ms | 31ms | -2ms | -6.01
| getFilePreview | avg | 42ms | 40ms | -2ms | -4.80
| removeUserCustomStatus | avg | 134ms | 129ms | -5ms | -3.73
| searchAllChannels | avg | 1.61s | 1.568s | -42ms | -2.61
| uploadFileStream | avg | 428ms | 420ms | -8ms | -1.87
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannel | p99 | 427ms | 5ms | -422ms | -98.91
| setPostReminder | p99 | 244ms | 25ms | -219ms | -89.74
| getPostThread | p99 | 454ms | 74ms | -380ms | -83.75
| createGroupChannel | p99 | 3.775s | 695ms | -3.08s | -81.59
| addChannelMember | p99 | 1.773s | 431ms | -1.342s | -75.71
| getPublicChannelsForTeam | p99 | 107ms | 30ms | -77ms | -71.86
| createDirectChannel | p99 | 1.18s | 497ms | -683ms | -57.88
| searchGroupChannels | p99 | 175ms | 85ms | -90ms | -51.43
| saveReaction | p99 | 485ms | 247ms | -238ms | -49.04
| getPostsForChannel | p99 | 856ms | 446ms | -410ms | -47.91
| getUsersByNames | p99 | 152ms | 80ms | -72ms | -47.39
| getChannelStats | p99 | 841ms | 456ms | -385ms | -45.76
| addTeamMember | p99 | 8.479s | 4.899s | -3.58s | -42.22
| searchPostsInTeam | p99 | 2.286s | 1.386s | -900ms | -39.38
| getTeamsUnreadForUser | p99 | 403ms | 249ms | -154ms | -38.21
| viewChannel | p99 | 307ms | 191ms | -116ms | -37.81
| getClientConfig | p99 | 117ms | 73ms | -44ms | -37.75
| getCategoriesForTeamForUser | p99 | 770ms | 483ms | -287ms | -37.25
| login | p99 | 744ms | 471ms | -273ms | -36.68
| getChannelMember | p99 | 431ms | 275ms | -156ms | -36.20
| autocompleteChannelsForTeamForSearch | p99 | 982ms | 646ms | -336ms | -34.21
| getThreadsForUser | p99 | 214ms | 145ms | -69ms | -32.20
| searchUsers | p99 | 592ms | 410ms | -182ms | -30.74
| getChannelMembersForTeamForUser | p99 | 223ms | 155ms | -68ms | -30.53
| updateReadStateThreadByUser | p99 | 497ms | 346ms | -151ms | -30.40
| getTeamMember | p99 | 7ms | 5ms | -2ms | -29.20
| getUsers | p99 | 232ms | 170ms | -62ms | -26.77
| getChannelsForUser | p99 | 427ms | 313ms | -114ms | -26.70
| getFileThumbnail | p99 | 206ms | 151ms | -55ms | -26.68
| getChannelsForTeamForUser | p99 | 242ms | 180ms | -62ms | -25.67
| createPost | p99 | 3.166s | 2.394s | -772ms | -24.39
| getPreferences | p99 | 277ms | 210ms | -67ms | -24.15
| getUser | p99 | 286ms | 220ms | -66ms | -23.09
| searchAllChannels | p99 | 8.383s | 6.45s | -1.933s | -23.06
| getAllTeams | p99 | 261ms | 205ms | -56ms | -21.47
| autocompleteUsers | p99 | 918ms | 732ms | -186ms | -20.26
| getTeamMembersForUser | p99 | 248ms | 203ms | -45ms | -18.11
| getTeamsForUser | p99 | 247ms | 206ms | -41ms | -16.57
| getPostsForChannelAroundLastUnread | p99 | 1.002s | 838ms | -164ms | -16.36
| createUser | p99 | 482ms | 419ms | -63ms | -13.07
| getFilePreview | p99 | 231ms | 218ms | -13ms | -5.62
| getChannelUnread | p99 | 217ms | 209ms | -8ms | -3.69
| getProfileImage | p99 | 474ms | 466ms | -8ms | -1.69
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.416
| BotStore.Get |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 92ms| 224ms | 132ms | 144.262
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 22ms| 21ms | -1ms | -4.496
| ChannelStore.Autocomplete |  Avg| 1.61s| 1.568s | -42ms | -2.609
| |  P99| 8.383s| 6.45s | -1.933s | -23.059
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 149ms| 124ms | -25ms | -16.789
| |  P99| 982ms| 646ms | -336ms | -34.214
| ChannelStore.CreateDirectChannel |  Avg| 46ms| 21ms | -25ms | -54.674
| |  P99| 510ms| 157ms | -353ms | -69.215
| ChannelStore.CreateInitialSidebarCategories |  Avg| 34ms| 27ms | -7ms | -20.779
| |  P99| 247ms| 223ms | -24ms | -9.704
| ChannelStore.Get |  Avg| 10ms| 7ms | -3ms | -29.371
| |  P99| 233ms| 190ms | -43ms | -18.447
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 16ms| 13ms | -3ms | -19.091
| |  P99| 249ms| 91ms | -158ms | -63.327
| ChannelStore.GetAllChannelMembersForUser |  Avg| 2ms| 1ms | -1ms | -64.712
| |  P99| 27ms| 24ms | -3ms | -11.137
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 18ms| 18ms | 0s | 0.000
| |  P99| 69ms| 69ms | 0s | 0.000
| ChannelStore.GetByName |  Avg| 15ms| 8ms | -7ms | -45.238
| |  P99| 239ms| 177ms | -62ms | -25.923
| ChannelStore.GetChannelUnread |  Avg| 6ms| 5ms | -1ms | -17.137
| |  P99| 217ms| 209ms | -8ms | -3.687
| ChannelStore.GetChannels |  Avg| 10ms| 5ms | -5ms | -49.152
| |  P99| 222ms| 151ms | -71ms | -32.018
| ChannelStore.GetChannelsByUser |  Avg| 46ms| 32ms | -14ms | -30.599
| |  P99| 409ms| 246ms | -163ms | -39.878
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 5ms| 3ms | -2ms | -37.932
| |  P99| 164ms| 79ms | -85ms | -51.711
| ChannelStore.GetFileCount |  Avg| 8ms| 5ms | -3ms | -37.785
| |  P99| 176ms| 82ms | -94ms | -53.500
| ChannelStore.GetGuestCount |  Avg| 32ms| 13ms | -19ms | -60.074
| |  P99| 427ms| 241ms | -186ms | -43.601
| ChannelStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 16ms | -2ms | -11.304
| ChannelStore.GetMemberCount |  Avg| 263ms| 163ms | -100ms | -38.042
| |  P99| 981ms| 855ms | -126ms | -12.850
| ChannelStore.GetMemberForPost |  Avg| 3ms| 2ms | -1ms | -37.971
| |  P99| 63ms| 27ms | -36ms | -57.021
| ChannelStore.GetMemberLastViewedAt |  Avg| 16ms| 8ms | -8ms | -51.095
| |  P99| 242ms| 188ms | -54ms | -22.298
| ChannelStore.GetMembersForUser |  Avg| 10ms| 5ms | -5ms | -51.451
| |  P99| 216ms| 144ms | -72ms | -33.351
| ChannelStore.GetMembersForUserWithPagination |  Avg| 44ms| 44ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.GetPinnedPostCount |  Avg| 11ms| 5ms | -6ms | -55.223
| |  P99| 237ms| 147ms | -90ms | -37.948
| ChannelStore.GetPublicChannelsForTeam |  Avg| 13ms| 10ms | -3ms | -22.473
| |  P99| 107ms| 30ms | -77ms | -71.864
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 55ms| 29ms | -26ms | -47.651
| |  P99| 768ms| 483ms | -285ms | -37.090
| ChannelStore.GetSidebarCategory |  Avg| 5ms| 4ms | -1ms | -22.072
| |  P99| 20ms| 10ms | -10ms | -49.985
| ChannelStore.GetTeamChannels |  Avg| 36ms| 48ms | 12ms | 33.140
| |  P99| 50ms| 239ms | 189ms | 379.899
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.494
| ChannelStore.InvalidateAllChannelMembersForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateChannelByName |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 16ms| 10ms | -6ms | -36.701
| |  P99| 213ms| 35ms | -178ms | -83.470
| ChannelStore.SaveMember |  Avg| 94ms| 57ms | -37ms | -39.372
| |  P99| 964ms| 735ms | -229ms | -23.745
| ChannelStore.SearchGroupChannels |  Avg| 6ms| 3ms | -3ms | -51.987
| |  P99| 175ms| 85ms | -90ms | -51.429
| ChannelStore.UpdateLastViewedAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 28ms| 43ms | 15ms | 52.937
| |  P99| 50ms| 447ms | 397ms | 797.907
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 12ms| 10ms | -2ms | -17.167
| CommandWebhookStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.GetByName |  Avg| 5ms| 2ms | -3ms | -56.289
| |  P99| 160ms| 67ms | -93ms | -58.107
| EmojiStore.GetMultipleByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 6ms| 7ms | 1ms | 16.126
| |  P99| 15ms| 22ms | 7ms | 47.677
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 59ms| 27ms | -32ms | -54.479
| FileInfoStore.GetForPost |  Avg| 3ms| 2ms | -1ms | -30.182
| |  P99| 90ms| 20ms | -70ms | -78.006
| FileInfoStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 11ms | 1ms | 10.060
| FileInfoStore.SetContent |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 14ms| 7ms | -7ms | -48.282
| |  P99| 236ms| 183ms | -53ms | -22.469
| GroupStore.GetByName |  Avg| 17ms| 8ms | -9ms | -53.314
| |  P99| 237ms| 188ms | -49ms | -20.651
| GroupStore.GetGroups |  Avg| 10ms| 6ms | -4ms | -40.081
| |  P99| 223ms| 165ms | -58ms | -26.025
| JobStore.Get |  Avg| 6ms| 2ms | -4ms | -67.375
| |  P99| 180ms| 23ms | -157ms | -87.465
| JobStore.GetAllByStatus |  Avg| 6ms| 4ms | -2ms | -34.255
| |  P99| 187ms| 117ms | -70ms | -37.433
| JobStore.GetCountByStatusAndType |  Avg| 8ms| 4ms | -4ms | -49.674
| |  P99| 213ms| 86ms | -127ms | -59.555
| JobStore.GetNewestJobByStatusesAndType |  Avg| 9ms| 5ms | -4ms | -46.053
| |  P99| 255ms| 100ms | -155ms | -60.784
| JobStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.331
| JobStore.UpdateOptimistically |  Avg| 5ms| 4ms | -1ms | -21.538
| |  P99| 21ms| 9ms | -12ms | -55.879
| JobStore.UpdateStatus |  Avg| 5ms| 4ms | -1ms | -21.479
| |  P99| 18ms| 18ms | 0s | 0.000
| JobStore.UpdateStatusOptimistically |  Avg| 5ms| 4ms | -1ms | -21.630
| |  P99| 10ms| 10ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 80ms| 71ms | -9ms | -11.261
| LinkMetadataStore.Save |  Avg| 4ms| 6ms | 2ms | 46.641
| |  P99| 10ms| 41ms | 31ms | 318.340
| PluginStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 15ms | -1ms | -6.171
| PluginStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.List |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 80ms| 40ms | -40ms | -50.000
| PluginStore.SetWithOptions |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PostAcknowledgementStore.GetForPost |  Avg| 9ms| 4ms | -5ms | -56.326
| |  P99| 178ms| 96ms | -82ms | -46.067
| PostAcknowledgementStore.GetForPosts |  Avg| 8ms| 4ms | -4ms | -47.541
| |  P99| 218ms| 94ms | -124ms | -56.841
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 5ms | -16ms | -77.482
| PostPersistentNotificationStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 5ms| 3ms | -2ms | -39.177
| |  P99| 161ms| 97ms | -64ms | -39.745
| PostPriorityStore.GetForPost |  Avg| 7ms| 5ms | -2ms | -27.861
| |  P99| 142ms| 187ms | 45ms | 31.690
| PostPriorityStore.GetForPosts |  Avg| 9ms| 4ms | -5ms | -57.267
| |  P99| 227ms| 96ms | -131ms | -57.633
| PostStore.AnalyticsPostCount |  Avg| 1.154s| 0s | -1.154s | -100.041
| |  P99| 2.485s| 0s | -2.485s | -99.989
| PostStore.Delete |  Avg| 13ms| 12ms | -1ms | -7.638
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 8ms| 6ms | -2ms | -26.414
| |  P99| 175ms| 93ms | -82ms | -46.757
| PostStore.GetEtag |  Avg| 14ms| 7ms | -7ms | -50.840
| |  P99| 245ms| 193ms | -52ms | -21.266
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 17ms | 1ms | 6.385
| PostStore.GetPostIdBeforeTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 4ms| 1ms | -3ms | -81.787
| |  P99| 46ms| 5ms | -41ms | -89.777
| PostStore.GetPostReminders |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 24ms| 22ms | -2ms | -8.430
| PostStore.GetPosts |  Avg| 20ms| 11ms | -9ms | -46.089
| |  P99| 244ms| 202ms | -42ms | -17.214
| PostStore.GetPostsAfter |  Avg| 8ms| 3ms | -5ms | -64.084
| |  P99| 211ms| 43ms | -168ms | -79.621
| PostStore.GetPostsBefore |  Avg| 8ms| 5ms | -3ms | -37.012
| |  P99| 198ms| 91ms | -107ms | -54.132
| PostStore.GetPostsByThread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 54ms| 43ms | -11ms | -20.245
| PostStore.GetPostsSince |  Avg| 14ms| 10ms | -4ms | -29.600
| |  P99| 211ms| 111ms | -100ms | -47.436
| PostStore.GetSingle |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 79ms| 65ms | -14ms | -17.718
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 48ms| 48ms | 0s | 0.000
| PostStore.SearchPostsForUser |  Avg| 97ms| 82ms | -15ms | -15.494
| |  P99| 2.071s| 1.386s | -685ms | -33.069
| PostStore.SetPostReminder |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 24ms| 10ms | -14ms | -58.824
| PostStore.Update |  Avg| 17ms| 17ms | 0s | 0.000
| |  P99| 44ms| 57ms | 13ms | 29.379
| PreferenceStore.DeleteCategoryAndName |  Avg| 3ms| 2ms | -1ms | -32.088
| |  P99| 10ms| 5ms | -5ms | -52.083
| PreferenceStore.Get |  Avg| 5ms| 3ms | -2ms | -38.983
| |  P99| 158ms| 81ms | -77ms | -48.593
| PreferenceStore.GetAll |  Avg| 24ms| 11ms | -13ms | -55.263
| |  P99| 249ms| 210ms | -39ms | -15.632
| PreferenceStore.Save |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 43ms| 41ms | -2ms | -4.639
| ProductNoticesStore.ClearOldNotices |  Avg| 2ms| 0s | -2ms | -91.087
| |  P99| 5ms| 0s | -5ms | -100.991
| ProductNoticesStore.View |  Avg| 36ms| 36ms | 0s | 0.000
| |  P99| 145ms| 125ms | -20ms | -13.752
| ReactionStore.GetForPost |  Avg| 4ms| 3ms | -1ms | -23.338
| |  P99| 88ms| 18ms | -70ms | -79.275
| RoleStore.ChannelHigherScopedPermissions |  Avg| 4ms| 1ms | -3ms | -79.284
| |  P99| 84ms| 5ms | -79ms | -94.611
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 21ms| 12ms | -9ms | -43.688
| |  P99| 247ms| 210ms | -37ms | -14.978
| SessionStore.GetSessionsExpired |  Avg| 13ms| 3ms | -10ms | -76.677
| |  P99| 97ms| 24ms | -73ms | -75.648
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 3ms| 2ms | -1ms | -29.931
| |  P99| 87ms| 49ms | -38ms | -43.731
| SessionStore.Remove |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| SessionStore.Save |  Avg| 23ms| 14ms | -9ms | -39.920
| |  P99| 243ms| 206ms | -37ms | -15.216
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| StatusStore.Get |  Avg| 13ms| 6ms | -7ms | -55.809
| |  P99| 218ms| 172ms | -46ms | -21.128
| StatusStore.GetByIds |  Avg| 3ms| 1ms | -2ms | -63.260
| |  P99| 126ms| 10ms | -116ms | -92.430
| StatusStore.SaveOrUpdate |  Avg| 37ms| 38ms | 1ms | 2.707
| |  P99| 451ms| 459ms | 8ms | 1.773
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| StatusStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| SystemStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 13ms | 0s | 0.000
| TeamStore.Get |  Avg| 4ms| 3ms | -1ms | -23.528
| |  P99| 128ms| 87ms | -41ms | -31.972
| TeamStore.GetAllPage |  Avg| 17ms| 9ms | -8ms | -45.891
| |  P99| 244ms| 198ms | -46ms | -18.823
| TeamStore.GetByName |  Avg| 9ms| 7ms | -2ms | -23.309
| |  P99| 263ms| 177ms | -86ms | -32.658
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 16ms| 8ms | -8ms | -49.991
| |  P99| 239ms| 195ms | -44ms | -18.414
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetTeamsByUserId |  Avg| 19ms| 10ms | -9ms | -47.966
| |  P99| 247ms| 206ms | -41ms | -16.599
| TeamStore.GetTeamsForUser |  Avg| 17ms| 8ms | -9ms | -51.477
| |  P99| 240ms| 197ms | -43ms | -17.952
| TeamStore.SaveMember |  Avg| 111ms| 104ms | -7ms | -6.279
| |  P99| 408ms| 296ms | -112ms | -27.448
| ThreadStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 5ms| 3ms | -2ms | -39.700
| |  P99| 141ms| 92ms | -49ms | -34.677
| ThreadStore.GetTeamsUnreadForUser |  Avg| 16ms| 9ms | -7ms | -42.725
| |  P99| 244ms| 198ms | -46ms | -18.841
| ThreadStore.GetThreadFollowers |  Avg| 5ms| 4ms | -1ms | -18.759
| |  P99| 162ms| 106ms | -56ms | -34.593
| ThreadStore.GetThreadForUser |  Avg| 7ms| 5ms | -2ms | -29.524
| |  P99| 175ms| 99ms | -76ms | -43.434
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 3ms| 2ms | -1ms | -38.979
| |  P99| 63ms| 40ms | -23ms | -36.720
| ThreadStore.GetThreadsForUser |  Avg| 7ms| 4ms | -3ms | -44.353
| |  P99| 191ms| 95ms | -96ms | -50.252
| ThreadStore.GetTotalThreads |  Avg| 14ms| 8ms | -6ms | -43.018
| |  P99| 234ms| 202ms | -32ms | -13.653
| ThreadStore.GetTotalUnreadMentions |  Avg| 12ms| 7ms | -5ms | -40.335
| |  P99| 229ms| 194ms | -35ms | -15.277
| ThreadStore.GetTotalUnreadThreads |  Avg| 14ms| 8ms | -6ms | -44.205
| |  P99| 231ms| 199ms | -32ms | -13.836
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 14ms| 8ms | -6ms | -42.094
| |  P99| 235ms| 204ms | -31ms | -13.209
| ThreadStore.MaintainMembership |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 21ms | 11ms | 114.187
| ThreadStore.MarkAsRead |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 1ms | -1ms | -43.208
| |  P99| 44ms| 5ms | -39ms | -88.136
| UserStore.AutocompleteUsersInChannel |  Avg| 231ms| 211ms | -20ms | -8.673
| |  P99| 949ms| 849ms | -100ms | -10.532
| UserStore.Count |  Avg| 123ms| 91ms | -32ms | -26.029
| |  P99| 465ms| 248ms | -217ms | -46.667
| UserStore.Get |  Avg| 3ms| 1ms | -2ms | -77.353
| |  P99| 48ms| 6ms | -42ms | -87.310
| UserStore.GetAllProfiles |  Avg| 17ms| 9ms | -8ms | -48.238
| |  P99| 222ms| 151ms | -71ms | -31.936
| UserStore.GetAllProfilesInChannel |  Avg| 624ms| 494ms | -130ms | -20.846
| |  P99| 2.429s| 2.245s | -184ms | -7.575
| UserStore.GetByUsername |  Avg| 5ms| 3ms | -2ms | -38.134
| |  P99| 103ms| 91ms | -12ms | -11.650
| UserStore.GetForLogin |  Avg| 18ms| 9ms | -9ms | -48.678
| |  P99| 248ms| 195ms | -53ms | -21.340
| UserStore.GetMany |  Avg| 2ms| 5ms | 3ms | 198.609
| |  P99| 5ms| 94ms | 89ms | 1797.980
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 12ms | -12ms | -50.895
| UserStore.GetProfilesByUsernames |  Avg| 5ms| 3ms | -2ms | -37.491
| |  P99| 152ms| 80ms | -72ms | -47.401
| UserStore.GetProfilesInChannel |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 9ms| 4ms | -5ms | -58.670
| |  P99| 280ms| 84ms | -196ms | -70.015
| UserStore.IsEmpty |  Avg| 11ms| 5ms | -6ms | -54.701
| |  P99| 204ms| 94ms | -110ms | -53.887
| UserStore.Save |  Avg| 71ms| 70ms | -1ms | -1.414
| |  P99| 163ms| 140ms | -23ms | -14.130
| UserStore.Search |  Avg| 105ms| 93ms | -12ms | -11.468
| |  P99| 607ms| 403ms | -204ms | -33.614
| UserStore.Update |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 10ms| 19ms | 9ms | 90.449
| UserStore.UpdateFailedPasswordAttempts |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.382
| UserStore.UpdateLastLogin |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 22ms| 21ms | -1ms | -4.600
| UserStore.UpdateUpdateAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| UserTermsOfServiceStore.GetByUser |  Avg| 19ms| 9ms | -10ms | -52.270
| |  P99| 248ms| 205ms | -43ms | -17.335
| WebhookStore.GetOutgoingByTeam |  Avg| 7ms| 5ms | -2ms | -27.982
| |  P99| 177ms| 89ms | -88ms | -49.714
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 226ms| 183ms | -43ms | -19.056
| | P99| 1.773s| 431ms | -1.342s | -75.712
| addTeamMember | Avg| 1.75s| 1.382s | -368ms | -21.023
| | P99| 8.479s| 4.899s | -3.58s | -42.220
| autocompleteChannelsForTeamForSearch | Avg| 149ms| 124ms | -25ms | -16.783
| | P99| 982ms| 646ms | -336ms | -34.214
| autocompleteUsers | Avg| 186ms| 161ms | -25ms | -13.475
| | P99| 918ms| 732ms | -186ms | -20.257
| createChannel | Avg| 36ms| 49ms | 13ms | 35.802
| | P99| 50ms| 239ms | 189ms | 379.899
| createDirectChannel | Avg| 227ms| 188ms | -39ms | -17.198
| | P99| 1.18s| 497ms | -683ms | -57.881
| createGroupChannel | Avg| 318ms| 275ms | -43ms | -13.531
| | P99| 3.775s| 695ms | -3.08s | -81.589
| createPost | Avg| 507ms| 421ms | -86ms | -16.975
| | P99| 3.166s| 2.394s | -772ms | -24.386
| createUser | Avg| 120ms| 105ms | -15ms | -12.453
| | P99| 482ms| 419ms | -63ms | -13.074
| deletePost | Avg| 17ms| 16ms | -1ms | -5.862
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getAllTeams | Avg| 19ms| 9ms | -10ms | -53.174
| | P99| 261ms| 205ms | -56ms | -21.466
| getCategoriesForTeamForUser | Avg| 55ms| 29ms | -26ms | -47.368
| | P99| 770ms| 483ms | -287ms | -37.251
| getChannel | Avg| 23ms| 3ms | -20ms | -87.596
| | P99| 427ms| 5ms | -422ms | -98.907
| getChannelMember | Avg| 28ms| 16ms | -12ms | -42.788
| | P99| 431ms| 275ms | -156ms | -36.201
| getChannelMembersForTeamForUser | Avg| 10ms| 6ms | -4ms | -38.689
| | P99| 223ms| 155ms | -68ms | -30.529
| getChannelStats | Avg| 32ms| 19ms | -13ms | -40.693
| | P99| 841ms| 456ms | -385ms | -45.761
| getChannelUnread | Avg| 6ms| 5ms | -1ms | -16.277
| | P99| 217ms| 209ms | -8ms | -3.687
| getChannelsForTeamForUser | Avg| 12ms| 7ms | -5ms | -41.634
| | P99| 242ms| 180ms | -62ms | -25.666
| getChannelsForUser | Avg| 47ms| 37ms | -10ms | -21.270
| | P99| 427ms| 313ms | -114ms | -26.696
| getClientConfig | Avg| 9ms| 8ms | -1ms | -10.974
| | P99| 117ms| 73ms | -44ms | -37.752
| getFilePreview | Avg| 42ms| 40ms | -2ms | -4.796
| | P99| 231ms| 218ms | -13ms | -5.619
| getFileThumbnail | Avg| 33ms| 31ms | -2ms | -6.015
| | P99| 206ms| 151ms | -55ms | -26.680
| getPostThread | Avg| 15ms| 9ms | -6ms | -39.302
| | P99| 454ms| 74ms | -380ms | -83.747
| getPostsForChannel | Avg| 42ms| 27ms | -15ms | -36.127
| | P99| 856ms| 446ms | -410ms | -47.907
| getPostsForChannelAroundLastUnread | Avg| 87ms| 48ms | -39ms | -45.071
| | P99| 1.002s| 838ms | -164ms | -16.359
| getPreferences | Avg| 24ms| 12ms | -12ms | -49.904
| | P99| 277ms| 210ms | -67ms | -24.153
| getProfileImage | Avg| 100ms| 93ms | -7ms | -7.016
| | P99| 474ms| 466ms | -8ms | -1.686
| getPublicChannelsForTeam | Avg| 15ms| 11ms | -4ms | -27.487
| | P99| 107ms| 30ms | -77ms | -71.864
| getRolesByNames | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 7ms| 5ms | -2ms | -29.197
| getTeamMembersForUser | Avg| 20ms| 9ms | -11ms | -56.297
| | P99| 248ms| 203ms | -45ms | -18.114
| getTeamsForUser | Avg| 19ms| 10ms | -9ms | -47.692
| | P99| 247ms| 206ms | -41ms | -16.571
| getTeamsUnreadForUser | Avg| 25ms| 13ms | -12ms | -47.885
| | P99| 403ms| 249ms | -154ms | -38.205
| getThreadsForUser | Avg| 9ms| 5ms | -4ms | -43.241
| | P99| 214ms| 145ms | -69ms | -32.196
| getUser | Avg| 22ms| 11ms | -11ms | -49.257
| | P99| 286ms| 220ms | -66ms | -23.095
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 19ms| 11ms | -8ms | -42.536
| | P99| 232ms| 170ms | -62ms | -26.775
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 5ms| 3ms | -2ms | -36.607
| | P99| 152ms| 80ms | -72ms | -47.385
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 96ms| 76ms | -20ms | -20.805
| | P99| 744ms| 471ms | -273ms | -36.678
| logout | Avg| 35ms| 35ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| patchPost | Avg| 34ms| 54ms | 20ms | 58.724
| | P99| 540ms| 1.21s | 670ms | 124.070
| removeUserCustomStatus | Avg| 134ms| 129ms | -5ms | -3.730
| | P99| 248ms| 248ms | 0s | 0.000
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 20ms| 9ms | -11ms | -56.281
| | P99| 485ms| 247ms | -238ms | -49.035
| searchAllChannels | Avg| 1.61s| 1.568s | -42ms | -2.608
| | P99| 8.383s| 6.45s | -1.933s | -23.059
| searchGroupChannels | Avg| 6ms| 3ms | -3ms | -51.469
| | P99| 175ms| 85ms | -90ms | -51.429
| searchPostsInTeam | Avg| 105ms| 86ms | -19ms | -18.070
| | P99| 2.286s| 1.386s | -900ms | -39.375
| searchUsers | Avg| 105ms| 94ms | -11ms | -10.454
| | P99| 592ms| 410ms | -182ms | -30.735
| setPostReminder | Avg| 46ms| 11ms | -35ms | -76.380
| | P99| 244ms| 25ms | -219ms | -89.737
| unfollowThreadByUser | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 24ms| 23ms | -1ms | -4.132
| updateCategoriesForTeamForUser | Avg| 39ms| 53ms | 14ms | 36.169
| | P99| 92ms| 447ms | 355ms | 387.232
| updatePreferences | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 30ms| 27ms | -3ms | -9.852
| | P99| 497ms| 346ms | -151ms | -30.403
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 428ms| 420ms | -8ms | -1.870
| | P99| 995ms| 994ms | -1ms | -0.101
| viewChannel | Avg| 18ms| 13ms | -5ms | -28.441
| | P99| 307ms| 191ms | -116ms | -37.815
